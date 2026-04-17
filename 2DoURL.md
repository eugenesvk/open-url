# ToDo
  - add an option to make short selection by mouse to select the whole  auto-detected link instead of currently where it opens the auto-detected link
  - ?(scoped delims should be enough?) allow passing delimiters as an argument
  - ? use custom command? respect default File Manager instead of forcing in File Explorer: change Windows default open command
  - [bug](https://github.com/noahcoad/open-url/issues/75) exception on opening the folder
  - ? TODO: add affordance and consider not just whether the selection includes mouse click point, but also whether that point is within X chars?
  - ? add menu for multi-link editing: view links in a scratch buffer new tab
    - but then how to open them without having to select everything?
      - add a command that treats every line (uncommented) as a URL?
# Done
  - ? use ↓ argument? add a command to select the auto-detected url if mouse drag happened (not open selection)
    + with keyboard: just another argument
  + [fr](https://github.com/noahcoad/open-url/issues/56) support relative links ?support `./relative` URLs
  + [fr](https://github.com/noahcoad/open-url/issues/63) open on where you click, not where the selection is at
  + [fr](https://github.com/noahcoad/open-url/issues/64) in md: support opening with cursor in `[any scope]` not just `(url)` 
  + option to disable modify path/google search commands, only let it open URL so that my mousemap doesn't generate noise if there is no url and there is no go_to_definition
  + ± make `C:\Users\User\AppData\Roaming\Sublime Text\Packages\Open URL\open_url.py` work even if you select only the middle
    - with custom expansion delimiters per scope and scoped delimiters

