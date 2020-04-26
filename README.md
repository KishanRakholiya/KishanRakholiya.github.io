## Important Commands

- Override Caps Lock with Backspace key on Mac OS Sierra
```ruby
hidutil property --set '{"UserKeyMapping":[{"HIDKeyboardModifierMappingSrc":0x700000039,
"HIDKeyboardModifierMappingDst":0x70000002A}]}'
```
- Testing Another Command
```ruby
git add .
git commit -m "<<Commit message>>"
```
- Git Rebase & Squash Commit
```ruby
git rebase mainline
git merge --squash <<branch_name>>
git commit .
```
