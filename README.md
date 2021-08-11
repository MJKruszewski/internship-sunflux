# First steps

## Prerequisite
- Create account on github and login to it `https://github.com/`

## #1 Setup
- Download git a `https://github.com/MJKruszewski/internship-sunflux.git`
- Download and install `https://code.visualstudio.com`
- Open Visual studio code
- Install extension to it from `https://code.visualstudio.com/docs/editor/github`
- After installation do instructions contained in 'Cloning repository' `https://code.visualstudio.com/docs/editor/github#_cloning-a-repository`, url to project which you need clone `https://github.com/MJKruszewski/internship-sunflux.git`  
- Click right mouse button on windows icon, then select PowerShell (as administrator) and run command `dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`
- Enter windows store, download and install `https://www.microsoft.com/store/productId/9N6SVWS3RX71`
- After installation of ubuntu, run it and then console should be present, after that enter this commands
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
bash
nvm install 14
node -v
sudo apt update
sudo apt install git
```
- Read article `https://docs.oracle.com/javase/tutorial/java/concepts/object.html`
- Read article `https://docs.oracle.com/javase/tutorial/java/concepts/class.html`
- Read article `https://docs.oracle.com/javase/tutorial/java/concepts/inheritance.html`
- Read article `https://docs.oracle.com/javase/tutorial/java/concepts/interface.html`
- Read article `https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html`

## #2 Lets start!
- Read article `https://www.typescriptlang.org/docs/handbook/2/everyday-types.html`
- Implement each type/structure mentioned in article above in your code, for example
```
const k: string = "test"

console.log("k value is: ", k)
```
- Think and list what advantages gives us usage of types
- Think and write down difference between const and let, with practical example 
- Meet with our new best friend - JSON - `https://www.w3schools.com/js/js_json_intro.asp`
- Try to create JSON object with usage of typescript, for now declare type of your variable as any ```const json: any = TODO```
- Refresh knowledge about loops
```
https://www.w3schools.com/js/js_loop_for.asp
https://www.w3schools.com/js/js_loop_while.asp
```
- Try to create your own loops, one with for, second with while - for now it should be just simple counting

## #3 Lets code!
- todo
