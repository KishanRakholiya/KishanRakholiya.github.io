## Important Commands

- Override Caps Lock with Backspace key on Mac OS Sierra
```ruby
hidutil property --set '{"UserKeyMapping":[{"HIDKeyboardModifierMappingSrc":0x700000039,
"HIDKeyboardModifierMappingDst":0x70000002A}]}'
```
- Git Add files to Staging area and Commit those files
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
- [Secure copy via SSH](https://linuxize.com/post/how-to-use-scp-command-to-securely-transfer-files/)
```ruby
scp file.txt <remote_username>@<10.10.0.2>:</remote/directory>
scp <source_username>@<source_10.10.0.2>:</source/directory> <destination_username>@<destination_10.10.0.2>:</destination/directory>
```
- [tar command](https://www.tecmint.com/18-tar-command-examples-in-linux/)
```ruby
create: tar -cvf <<file_name>>.tar /<<location/...>>
extract: tar -xvf <<file_name>>.tar -C <</location_to_extract>>
```

- [vim command](https://www.keycdn.com/blog/vim-commands) - [vim regex](http://vimregex.com/)
```ruby
:set nu - Sets file number
:%s/<<pattern>>/<<replacement>>/gc - Replaces all occurrences of a pattern and confirms each one
:set hlsearch - Highlight searched word
```
