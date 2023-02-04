# TypeScript-Basics

(TS-Config)

Steps
1. tsc -innit in terminal to create tsconfig.json file
2. Use rootDir and add .ts location inside
3. Use outDir and rename it to ./dist
4. Use removeComments
5. Use no EmitOnError
6. Run tsc in terminal to get index.js in dist folder


(Debugging TypeScript Application)

Steps
1. In tsconfig.json file Use sourceMap
2. In terminal use tsc to get index.js.map

Break Point

![image](https://user-images.githubusercontent.com/59819674/216784380-c0efc55e-a0c8-4fb7-a441-fa331a673306.png)

3. In debug create a launch.json file and select node.js
4. In launch.json add after program line preLaunchTask "tsc: build - tsconfig.json"
5. Go back to debug panel and run program
6. In Watch we can watch variable
