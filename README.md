# PWAsandbox

1. Run the build once to create the www folder  
npm run build

2. Add the android and electron platforms
npx cap add android
npx cap add electron

3. Copy the files to the android and electron folders
npx cap copy

4. Build and serve the app based on the target platform
To serve as a webapp, run:
npx cap serve
