--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 




⢸⣿⣟⣷⢿⣯⡿⠛⠓⠛⠻⣽⣿⣾⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣯⣿⣞⣯⣷⢿⣯⣿⣽⣻⡷⣯⣟⣿⡇
⢸⣿⣟⣾⢿⡞⠀⠀⠀⣤⣤⣿⠁⠀⠀⣌⠉⠙⣿⡿⠋⠀⢠⠀⠈⠻⣿⠀⠀⠀⠀⠀⣿⡟⠁⠀⡄⠀⠙⢾⣿⡿⠿⠿⠿⢿⣿⣽⣻⡇
⢸⣿⣟⣾⢿⡇⠀⠀⠸⣿⡿⣿⡁⠀⠀⠁⠀⢰⣿⡇⠀⠀⣸⠀⠀⠀⣿⡿⠃⠀⢀⣼⣿⠀⠀⠀⡇⠀⠀⢸⣿⠀⠀⠦⠀⢈⣿⣯⣿⡇
⢸⣿⣟⣾⢿⣷⣄⠀⠀⠀⣀⣿⡆⠀⣀⣷⡀⣀⣽⣷⣀⠀⠘⠀⢀⣴⣿⡀⢀⠀⡀⢀⣿⣦⡀⠀⠇⠀⣠⣾⣿⣶⣶⣶⣶⣾⣿
]]--

local v0=game:GetService("TweenService");local v1=game:GetService("UserInputService");local v2=game:GetService("HttpService");local v3=game:GetService("Players");local v4=Instance.new("ScreenGui");v4.Parent=v3.LocalPlayer:WaitForChild("PlayerGui");local v6=UDim2.new(0.7,0,0.7,0);local v7=Instance.new("Frame");v7.Size=v6;v7.Position=UDim2.new(0.15,0,1,0);v7.BackgroundColor3=Color3.fromRGB(0,0,0);v7.BorderSizePixel=0;v7.ClipsDescendants=true;v7.Active=true;v7.Parent=v4;local v15=Instance.new("UICorner");v15.CornerRadius=UDim.new(0,20);v15.Parent=v7;local v18=Instance.new("ImageLabel");v18.Size=UDim2.new(1,0,1,0);v18.Position=UDim2.new(0,0,0,0);v18.Image="rbxassetid://82810701493684";v18.BackgroundTransparency=1;v18.ScaleType=Enum.ScaleType.Crop;v18.Visible=false;v18.Parent=v7;local v27=Instance.new("UICorner");v27.CornerRadius=UDim.new(0,20);v27.Parent=v18;local v30=Instance.new("TextLabel");v30.Size=UDim2.new(1,0,0.15,0);v30.Position=UDim2.new(0,0,0.1,0);v30.Text="CHANGE LANGUAGE";v30.TextColor3=Color3.fromRGB(255,255,255);v30.TextSize=40;v30.Font=Enum.Font.SourceSansBold;v30.BackgroundTransparency=1;v30.Visible=false;v30.Parent=v7;local v41=Instance.new("TextLabel");v41.Size=UDim2.new(1,0,0.1,0);v41.Position=UDim2.new(0,0,0.25,0);v41.Text="By: CKARLO HUB";v41.TextColor3=Color3.fromRGB(255,255,255);v41.TextSize=30;v41.Font=Enum.Font.SourceSansBold;v41.BackgroundTransparency=1;v41.Visible=false;v41.Parent=v7;local v51=Instance.new("TextButton");v51.Size=UDim2.new(0.4,0,0.15,0);v51.Position=UDim2.new(0.1,0,0.7,0);v51.Text="ARABIC";v51.TextColor3=Color3.fromRGB(255,255,255);v51.TextSize=35;v51.Font=Enum.Font.SourceSansBold;v51.BackgroundColor3=Color3.fromRGB(50,50,50);v51.BorderSizePixel=0;v51.Visible=false;v51.Parent=v7;local v62=Instance.new("UICorner");v62.CornerRadius=UDim.new(0,20);v62.Parent=v51;local v65=Instance.new("TextButton");v65.Size=UDim2.new(0.4,0,0.15,0);v65.Position=UDim2.new(0.5,0,0.7,0);v65.Text="English";v65.TextColor3=Color3.fromRGB(255,255,255);v65.TextSize=35;v65.Font=Enum.Font.SourceSansBold;v65.BackgroundColor3=Color3.fromRGB(50,50,50);v65.BorderSizePixel=0;v65.Visible=false;v65.Parent=v7;local v76=Instance.new("UICorner");v76.CornerRadius=UDim.new(0,20);v76.Parent=v65;local function v79(v83,v84,v85) local v86=TweenInfo.new(v85,Enum.EasingStyle.Quad,Enum.EasingDirection.Out);local v87=v0:Create(v83,v86,{Position=v84});v87:Play();end local function v80() local v88=TweenInfo.new(0.3,Enum.EasingStyle.Quad,Enum.EasingDirection.Out);local v89=v0:Create(v18,v88,{ImageTransparency=1});v89:Play();v30.Visible=true;v41.Visible=true;v51.Visible=true;v65.Visible=true;v0:Create(v30,v88,{TextTransparency=0}):Play();v0:Create(v41,v88,{TextTransparency=0}):Play();v0:Create(v51,v88,{BackgroundTransparency=0}):Play();v0:Create(v65,v88,{BackgroundTransparency=0}):Play();end local function v81() local v94=Instance.new("Frame");v94.Size=UDim2.new(0.5,0,0.4,0);v94.Position=UDim2.new(0.25,0,0.3,0);v94.BackgroundColor3=Color3.fromRGB(30,30,30);v94.BorderSizePixel=0;v94.ClipsDescendants=true;v94.Parent=v4;local v101=Instance.new("UICorner");v101.CornerRadius=UDim.new(0,20);v101.Parent=v94;local v104=Instance.new("TextLabel");v104.Size=UDim2.new(1,0,0.2,0);v104.Position=UDim2.new(0,0,0.05,0);v104.Text="KEY SYSTEM";v104.TextColor3=Color3.fromRGB(255,255,255);v104.TextSize=25;v104.Font=Enum.Font.SourceSansBold;v104.BackgroundTransparency=1;v104.Parent=v94;local v114=Instance.new("TextBox");v114.Size=UDim2.new(0.8,0,0.2,0);v114.Position=UDim2.new(0.1,0,0.3,0);v114.PlaceholderText="ENTER KEY HERE";v114.Text="";v114.TextColor3=Color3.fromRGB(255,255,255);v114.TextSize=20;v114.BackgroundColor3=Color3.fromRGB(50,50,50);v114.BorderSizePixel=0;v114.Parent=v94;local v124=Instance.new("UICorner");v124.CornerRadius=UDim.new(0,10);v124.Parent=v114;local v127=Instance.new("TextButton");v127.Size=UDim2.new(0.3,0,0.2,0);v127.Position=UDim2.new(0.35,0,0.6,0);v127.Text="COPY LINK";v127.TextColor3=Color3.fromRGB(255,255,255);v127.TextSize=18;v127.BackgroundColor3=Color3.fromRGB(70,70,70);v127.BorderSizePixel=0;v127.Parent=v94;local v136=Instance.new("UICorner");v136.CornerRadius=UDim.new(0,10);v136.Parent=v127;v127.MouseButton1Click:Connect(function() local v186="http://easy4skip.com/Keyy";setclipboard(v186);local v187=Instance.new("TextLabel");v187.Size=UDim2.new(0.5,0,0.1,0);v187.Position=UDim2.new(0.25,0,0.8,0);v187.Text=" LINK COPIED";v187.TextColor3=Color3.fromRGB(255,255,255);v187.TextSize=18;v187.BackgroundColor3=Color3.fromRGB(50,50,50);v187.BorderSizePixel=0;v187.Parent=v94;local v196=Instance.new("UICorner");v196.CornerRadius=UDim.new(0,10);v196.Parent=v187;wait(2);v187:Destroy();end);v114.FocusLost:Connect(function() local v199="B5Z8M4";if (v114.Text==v199) then local v214=Instance.new("TextLabel");v214.Size=UDim2.new(0.5,0,0.1,0);v214.Position=UDim2.new(0.25,0,0.8,0);v214.Text=" KEY IS CORRECT!";v214.TextColor3=Color3.fromRGB(0,255,0);v214.TextSize=18;v214.BackgroundColor3=Color3.fromRGB(50,50,50);v214.BorderSizePixel=0;v214.Parent=v94;local v223=Instance.new("UICorner");v223.CornerRadius=UDim.new(0,10);v223.Parent=v214;wait(1);v94:Destroy();v7:Destroy();print(" Script done!");loadstring(game:HttpGet("https://pastebin.com/raw/CS6UUNiK"))();else local v226=Instance.new("TextLabel");v226.Size=UDim2.new(0.5,0,0.1,0);v226.Position=UDim2.new(0.25,0,0.8,0);v226.Text="Key isincorrect!";v226.TextColor3=Color3.fromRGB(255,0,0);v226.TextSize=18;v226.BackgroundColor3=Color3.fromRGB(50,50,50);v226.BorderSizePixel=0;v226.Parent=v94;local v235=Instance.new("UICorner");v235.CornerRadius=UDim.new(0,10);v235.Parent=v226;wait(2);v226:Destroy();end end);end local function v82() local v139=Instance.new("Frame");v139.Size=UDim2.new(0.5,0,0.4,0);v139.Position=UDim2.new(0.25,0,0.3,0);v139.BackgroundColor3=Color3.fromRGB(30,30,30);v139.BorderSizePixel=0;v139.ClipsDescendants=true;v139.Parent=v4;local v146=Instance.new("UICorner");v146.CornerRadius=UDim.new(0,20);v146.Parent=v139;local v149=Instance.new("TextLabel");v149.Size=UDim2.new(1,0,0.2,0);v149.Position=UDim2.new(0,0,0.05,0);v149.Text="Key System";v149.TextColor3=Color3.fromRGB(255,255,255);v149.TextSize=25;v149.Font=Enum.Font.SourceSansBold;v149.BackgroundTransparency=1;v149.Parent=v139;local v159=Instance.new("TextBox");v159.Size=UDim2.new(0.8,0,0.2,0);v159.Position=UDim2.new(0.1,0,0.3,0);v159.PlaceholderText="Enter the key here";v159.Text="";v159.TextColor3=Color3.fromRGB(255,255,255);v159.TextSize=20;v159.BackgroundColor3=Color3.fromRGB(50,50,50);v159.BorderSizePixel=0;v159.Parent=v139;local v169=Instance.new("UICorner");v169.CornerRadius=UDim.new(0,10);v169.Parent=v159;local v172=Instance.new("TextButton");v172.Size=UDim2.new(0.3,0,0.2,0);v172.Position=UDim2.new(0.35,0,0.6,0);v172.Text="Copy Link";v172.TextColor3=Color3.fromRGB(255,255,255);v172.TextSize=18;v172.BackgroundColor3=Color3.fromRGB(70,70,70);v172.BorderSizePixel=0;v172.Parent=v139;local v181=Instance.new("UICorner");v181.CornerRadius=UDim.new(0,10);v181.Parent=v172;v172.MouseButton1Click:Connect(function() local v200="http://easy4skip.com/Keyy";setclipboard(v200);local v201=Instance.new("TextLabel");v201.Size=UDim2.new(0.5,0,0.1,0);v201.Position=UDim2.new(0.25,0,0.8,0);v201.Text="Link copied to clipboard!";v201.TextColor3=Color3.fromRGB(255,255,255);v201.TextSize=18;v201.BackgroundColor3=Color3.fromRGB(50,50,50);v201.BorderSizePixel=0;v201.Parent=v139;local v210=Instance.new("UICorner");v210.CornerRadius=UDim.new(0,10);v210.Parent=v201;wait(2);v201:Destroy();end);v159.FocusLost:Connect(function() local v213="B5Z8M4";if (v159.Text==v213) then local v238=Instance.new("TextLabel");v238.Size=UDim2.new(0.5,0,0.1,0);v238.Position=UDim2.new(0.25,0,0.8,0);v238.Text="Key is correct!";v238.TextColor3=Color3.fromRGB(0,255,0);v238.TextSize=18;v238.BackgroundColor3=Color3.fromRGB(50,50,50);v238.BorderSizePixel=0;v238.Parent=v139;local v247=Instance.new("UICorner");v247.CornerRadius=UDim.new(0,10);v247.Parent=v238;wait(1);v139:Destroy();v7:Destroy();print("Script executed!");loadstring(game:HttpGet("https://pastebin.com/raw/CS6UUNiK"))();else local v250=Instance.new("TextLabel");v250.Size=UDim2.new(0.5,0,0.1,0);v250.Position=UDim2.new(0.25,0,0.8,0);v250.Text="Key is incorrect!";v250.TextColor3=Color3.fromRGB(255,0,0);v250.TextSize=18;v250.BackgroundColor3=Color3.fromRGB(50,50,50);v250.BorderSizePixel=0;v250.Parent=v139;local v259=Instance.new("UICorner");v259.CornerRadius=UDim.new(0,10);v259.Parent=v250;wait(2);v250:Destroy();end end);end v79(v7,UDim2.new(0.15,0,0.15,0),1);wait(0.5);v18.Visible=true;v0:Create(v18,TweenInfo.new(0.2,Enum.EasingStyle.Quad,Enum.EasingDirection.Out),{ImageTransparency=0}):Play();wait(3);v80();v51.MouseButton1Click:Connect(function() v7.Visible=false;v81();end);v65.MouseButton1Click:Connect(function() v7.Visible=false;v82();end);
