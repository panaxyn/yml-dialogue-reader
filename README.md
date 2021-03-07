# yml-dialogue-reader
A small program to help you get dialogue text from a .yml file into .txt and back

## Quick manual
1) Unpack the archive with the files wherever you wish. Inside you will find the .exe file, you'll only need to launch this one, don't mind the other files.
2) Once you launch it, you'll be met with an exhaustingly descriptive menu:
#### ![image](https://user-images.githubusercontent.com/12386519/110238361-4a911500-7f52-11eb-9e74-eaaeb4f66e0d.png)
3) To generate a .txt file, click on the "Extract" button and browse or copy the path in the input box to the **.yml** file and click "Open". The program will close after that without any messages, so don't worry, that's intended. The generated file can be found in the "\translations" folder, where the .exe file is.
#### ![image](https://user-images.githubusercontent.com/12386519/110238705-27676500-7f54-11eb-8f15-7acdd97718a2.png)
4) Once you're happy with what you have in your .txt file, launch the .exe again, but this time click on the "Update" button and choose the **.yml** file you want to be updated. Ta-daa, it's done!!

**PLEASE NOTE**, that the program works in a way that it only updates the .yml files which have the .txt files generated for them in the "\translations" folder. So, for example:
* WILL WORK ✅:
  - You have "sidequest_dreamworld_bed.txt" in the \translation folder and try to update "sidequest_dreamworld_bed.yml"
* WON'T WORK ❌:
  - You **don't** have "sidequest_dreamworld_bed.txt" in the \translation folder and try to update "sidequest_dreamworld_bed.yml"
  - You have **any files besides** "sidequest_dreamworld_bed.txt" in the \translation folder and you try to update "sidequest_dreamworld_bed.yml"

## Misc
There are still things in need of tweaking a bit and maybe just in general some cosmetic upgrades to come (especially if there's gonna be demand for it), but the main functionality is there. If there are any further questions, things in need of clarification, or, much more probably, something breaks the program, feel free to shoot a question here or dm me on discord ("panaxyn", pretty sure 90% of the people reading it saw me at least somewhere).
