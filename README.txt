Getting the APK (steps in English as shown on GitHub):
1) github.com > Sign up / Sign in > "+" (top right) > New repository > name: quran-radio-web > Public > Create repository.
2) Click "uploading an existing file", drag ALL files/folders from this folder (package.json, capacitor.config.json, www, .github, .gitignore) > Commit changes.
   If the .github folder does not upload: Add file > Create new file > name it .github/workflows/build-apk.yml and paste the file contents > Commit.
3) Open the Actions tab. "Build Android APK" starts by itself (8-12 min). If not: select it > Run workflow.
4) When it has a green check, go to the repository main page > Releases (right side) > download tanaffas-quran-radio.apk and install it on your phone.
If the run fails: open it > click the red step > copy the last ~20 lines and send them to Claude.
