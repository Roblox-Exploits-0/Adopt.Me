local scripts = {
    tizz = "https://raw.githubusercontent.com/BloxZilla/w/refs/heads/main/POO%20POO",
    gui = "https://raw.githubusercontent.com/BloxZilla/Adopt.Me/refs/heads/main/new.dup3r"
}

for name, url in pairs(scripts) do
    local success, response = pcall(function()
        return game:HttpGet(url)
    end)

    if success then
        print("Loaded " .. name)
        loadstring(response)()
    else
        warn("Failed to load " .. name .. ": " .. tostring(response))
    end
end
