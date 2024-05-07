# Mac defaults

## Increase arrow keys velocity

`defaults write NSGlobalDomain KeyRepeat -int 1`  
`defaults write NSGlobalDomain InitialKeyRepeat -int 12`

## Only show open applications in dock

`defaults write com.apple.dock "static-only" -bool "true" && killall Dock`
