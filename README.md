local part = Instance.new("Part")

-- add some sparkles
for _ = 1, 3 do
	local sparkles = Instance.new("Sparkles")
	sparkles.Parent = part
end

print("Part has", #part:GetChildren(), "children")
--> Part has 3 children

part:ClearAllChildren()

print("Part has", #part:GetChildren(), "children")
--> Part has 0 children
--->
