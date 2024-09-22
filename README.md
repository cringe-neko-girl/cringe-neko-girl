
# About Me

<img src="https://ih1.redbubble.net/image.5090038845.1125/raf,360x360,075,t,fafafa:ca443f4786.u9.jpg" width="130px height=100%" align="left" />

 [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord)](https://discord.gg/nmrAVfva)

```powershell 
# Set basic details
$nickname = "Senko"
$gender = "Male"

# Display user info
echo "User: <@1124389055598170182>"

# Personality
$personality = @{
    "Trait1" = "Playful"
    "Trait2" = "Enthusiastic"
}

# Interests
$interests = @("Anime", "Discord", "Coding")
$favorite_anime = "Clannad"

# Skills
$skills = @("Discord Bot Development", "Python Programming")

# Goals
$goal = "Pursuing a BS in Computer Science"
$status = "Currently in college..."

# Inspiration
$inspiration = "Oliver (Creator of Poketwo)"

# Output the information
echo "`n# Personality"
$personality.GetEnumerator() | ForEach-Object { echo "$($_.Key): $($_.Value)" }

echo "`n# Interests"
$interests | ForEach-Object { echo "Interest: $_" }
echo "Favorite Anime: $favorite_anime"

echo "`n# Skills"
$skills | ForEach-Object { echo "Skill: $_" }

echo "`n# Goals"
echo "Goal: $goal"
echo "Status: $status"

echo "`n# Inspiration"
echo "Inspiration: $inspiration"

```

