# 📤 GitHub Upload Guide

## Method A: Web Interface (Recommended)

### Step 1: Prepare Files
1. HTMLRunner folder ko zip karein
2. Ya individual files upload karein

### Step 2: Upload via GitHub Web
1. Repository page pe "uploading an existing file" link dabayein
2. Files drag & drop karein ya "choose your files" se select karein
3. Commit message likhein: "Initial Android HTML Runner app"
4. "Commit changes" dabayein

## Method B: Git Commands (Advanced)

```bash
# Repository clone karein
git clone https://github.com/YOUR_USERNAME/HTMLRunner.git

# HTMLRunner folder mein files copy karein
# Phir:
cd HTMLRunner
git add .
git commit -m "Initial Android HTML Runner app"
git push origin main
```

## Method C: GitHub Desktop (GUI)

1. GitHub Desktop download karein
2. Repository clone karein
3. Files copy karein
4. Commit aur push karein

## Files to Upload:
✅ app/ folder (complete)
✅ gradle/ folder
✅ .github/ folder (for Actions)
✅ build.gradle
✅ settings.gradle
✅ gradle.properties
✅ gradlew
✅ gradlew.bat
✅ README.md

## After Upload:
1. Actions tab check karein
2. Workflow run hone ka wait karein
3. APK download karein from artifacts