# NOTICE: This is now built into the [gitstats](https://github.com/TaylorMichaelHall/gitstats) cli and this repo will be archived.

# Git Contribution Counter

This Go script analyzes Git repository contributions, displaying a bar graph of commits per contributor and allowing for detailed contributor information.

## Usage

Run the script with:

```
git clone https://github.com/TaylorMichaelHall/git-contributions-counter
cd git-contributions-counter
go run main.go <path_to_git_repo>
```

Follow the prompts to view detailed information about specific contributors.

## Requirements

- Go
- Git (accessible in PATH)
- A local Git repository to analyze
