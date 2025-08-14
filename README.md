# sigmafox
pretty simple css for compact sidebar workflow - supports all operating systems (mac, win, linux)

## screenshots

<img width="800" height="1024" alt="Screenshot 2025-08-13 at 11 06 46 PM" src="https://github.com/user-attachments/assets/61ccb67c-3059-461e-991d-552ff87ba3cd" />

#### centered floating search bar - activate with cmd + L / ctrl + L
<img width="800" height="1176" alt="Screenshot 2025-08-13 at 11 18 00 PM" src="https://github.com/user-attachments/assets/a85cc564-d917-442b-8491-3bb60b3a1475" />

#### top bar expands on hover
<img width="800" height="1024" alt="Screenshot 2025-08-13 at 11 01 42 PM" src="https://github.com/user-attachments/assets/703c0087-7304-4cc6-aca5-26ece9aaddd3" />

#### i like it with the adaptive tab bar color extension - set tab bar darkness to -10%. some examples:
<img width="800" height="1024" alt="Screenshot 2025-08-13 at 11 05 43 PM" src="https://github.com/user-attachments/assets/f2101e8e-5fd9-49d1-a440-52306ac84558" />
<img width="800" height="980" alt="Screenshot 2025-08-13 at 11 08 19 PM" src="https://github.com/user-attachments/assets/a20dd80f-b5a0-4246-8532-b3ce2c311d07" />

## installation

0. go to about:config in your URL bar, search for toolkit.legacyUserProfileCustomizations.stylesheets and set it to true
1. locate the firefox profile folder by going to the _hamburger menu_ > _help_ > _more torubleshooting information_
2. click _show in finder_ or _open folder_ next to profile folder
3. open the highlighted folder (should look something like "13s123f4.default-release")
5. `git clone https://github.com/nathandaven/sigmafox.git chrome` and restart firefox (command-q/alt-f4 and reopen)
    > alternatively, just create a folder inside the profile called "chrome" and put `userChrome.css` inside
7. enable sidebar tabs, optionally enable compact mode (`browser.compactmode.show` in about:config and then change setting in customize toolbar screen), and install adaptive tab color extension
8. youll probably wanna move your extensions around in the top bar to what you care about most
10. profit. this is a simple theme so its not perfect

