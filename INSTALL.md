### [IDA](https://www.hex-rays.com/products/ida/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/ida.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/ida/archive/master.zip) option and unzip them.

#### Activating theme

### IDA <= 7.3
1. Open your IDA <= 7.3
2. Go to `Options` > `Colors` > `Import`
3. Select the file (`dracula-theme.clr`)
4. **Done!**

### IDA >= 7.3
1. Create a folder called dracula in IDA themes folder
    - On Windows: `C:\Program Files\IDA...\themes\dracula`
    - On Linux: `~/.ida.../themes/dracula/`

2. Move the file `theme.css` to dracula folder
    - `mv theme.css ~/.ida.../themes/dracula/`

3. Open your IDA >= 7.3
4. Go to `Options` > `Colors` Click on the box Current theme > Select `dracula`
5. **Done!**