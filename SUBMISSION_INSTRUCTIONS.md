# Microphone Input Applet - Spices Submission Guide

## Files Ready for Submission

Your applet is prepared in: `~/Documents/GitHub/mic-input-spices/mic-input/`

Directory structure (follows Cinnamon Spices requirements):
```
mic-input/
├── info.json                    # Author information
├── README.md                    # Documentation
├── icon.png                     # 512x512 applet icon
├── screenshot.png               # Screenshot
└── files/
    └── mic-input/
        ├── applet.js            # Main applet code
        ├── metadata.json        # Applet metadata
        └── LICENSE              # GPL-3.0 license
```

This structure is required:
- Root `mic-input/` directory contains documentation and metadata
- `files/mic-input/` contains the actual applet code that gets installed

## Submission Steps

### 1. Fork the Cinnamon Spices Repository

Visit: https://github.com/linuxmint/cinnamon-spices-applets

Click "Fork" to create your own copy.

### 2. Clone Your Fork

```bash
cd ~/Documents/GitHub
git clone https://github.com/YOUR_USERNAME/cinnamon-spices-applets.git
cd cinnamon-spices-applets
```

### 3. Copy Your Applet

```bash
cp -r ~/mic-input-spices/mic-input ./mic-input
```

### 4. Review Contribution Guidelines

Read: https://github.com/linuxmint/cinnamon-spices-applets/blob/master/CONTRIBUTING.md

Key requirements:
- Applet must work on latest Cinnamon version
- Code should be clean and well-commented
- No hardcoded paths to user directories
- Follow existing applet patterns

### 5. Create a Commit

```bash
git add mic-input/
git commit -m "Add Microphone Input Level applet

A simple applet to display and control microphone input volume
with mute toggle and volume slider in the panel popup menu."
```

### 6. Push to Your Fork

```bash
git push origin master
```

### 7. Create Pull Request

1. Go to your fork on GitHub
2. Click "Pull Request"
3. Write a description explaining what your applet does
4. Submit the PR

### 8. Wait for Review

The Cinnamon Spices maintainers will:
- Review your code
- Test the applet
- Provide feedback or approve

## Additional Notes

- Be responsive to reviewer feedback
- They may ask for changes before merging
- Once merged, your applet will appear in the Cinnamon Applets download section

## Alternative: Upload to Cinnamon Spices Website

You can also submit directly through:
https://cinnamon-spices.linuxmint.com/

This requires creating an account and uploading your files through their web interface.

---

Good luck with your submission!
