
# About Me

<img src="https://ih1.redbubble.net/image.5090038845.1125/raf,360x360,075,t,fafafa:ca443f4786.u9.jpg" width="130px height=100%" align="left" />

 [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord)](https://discord.gg/nmrAVfva)

```powershell 
function Set-UserProfile {
    # Set basic information
    $nickname = "Senko"
    $gender = "Male"
    $userID = "<@1124389055598170182>"

    # Set personality
    $personality = @{
        Playful = $true
        Enthusiastic = $true
    }

    # Set interests
    $interests = @("Anime", "Discord", "Coding")
    $favorite_anime = "Clannad"

    # Set skills
    $skills = @("Discord Bot Development", "Python Programming")

    # Set goals and status
    $goal = "Pursuing a BS in Computer Science"
    $status = "Currently in college..."

    # Set inspiration
    $inspiration = "Oliver (Creator of Poketwo)"

    # Output the profile
    Write-Host "Nickname: $nickname"
    Write-Host "Gender: $gender"
    Write-Host "User: $userID"
    Write-Host "`n# Personality"
    Write-Host "Playful: $($personality.Playful)"
    Write-Host "Enthusiastic: $($personality.Enthusiastic)"
    Write-Host "`n# Interests"
    $interests | ForEach-Object { Write-Host "Interest: $_" }
    Write-Host "Favorite Anime: $favorite_anime"
    Write-Host "`n# Skills"
    $skills | ForEach-Object { Write-Host "Skill: $_" }
    Write-Host "`n# Goals"
    Write-Host "Goal: $goal"
    Write-Host "Status: $status"
    Write-Host "`n# Inspiration"
    Write-Host "Inspiration: $inspiration"
}

# Run the function
Set-UserProfile

```

