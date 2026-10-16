# Phantom I

A native macOS creative media toolkit.

Phantom I brings creative workflows together in one application, including graphic design, photo editing, video editing, colour grading, motion blur, and more.
<p align="center">
  <img
    src="https://github.com/user-attachments/assets/5ad5d784-6d8a-4d0a-b300-d3a155afd767"
    alt="Phantom Logo 1"
    width="160"
  />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img
    src="https://github.com/user-attachments/assets/2e3bb91e-d06f-4b3b-b1ec-29fa10f57c3d"
    alt="Phantom Logo 2"
    width="160"
  />
</p>

## Download

Download the latest version of Phantom I from the [Releases](../../releases) page.
Unfortunately Phantom isn't signed by MacOS as it requires an Apple Developer subscription which is paid and this is a casual project. 
Therefore you will need to proceed with the following steps the first time you install Phantom. Method 1 or Method 2.

**Method 1**
  1. Open Terminal
  2. Copy and paste this string: ```xattr -dr com.apple.quarantine /Applications/Phantom.app```
  3. Open Phantom

 **Method 2**
  1. Open Phantom
  2. Go to your Mac's "Privacy and Security" in Settings
  3. Scroll to the bottom
  4. Click "Open Anyway" for Phantom.

### Current Version

**Phantom I v0.7.5 (Build 12)**

Platform: macOS

### Installation

1. Download the DMG installer.
2. Open the DMG.
3. Drag Phantom into Applications.
4. Open Phantom from Applications.

Phantom I is currently distributed without Apple notarisation. macOS may require you to approve the application through System Settings → Privacy & Security → Open Anyway. See the above methods 1 & 2 for help.

## Website

Visit the official Phantom website for more information.
getphantom.pages.dev

# Troubleshooting

## Phantom Will Not Open

First, confirm that Phantom was copied into your Applications folder.

Try the following:

1. Close Phantom if it is running.
2. Open Finder.
3. Navigate to Applications.
4. Locate Phantom.
5. Attempt to open it again.
6. Check System Settings → Privacy & Security for an approval option.

If macOS reports that the application is damaged, cannot be verified, or cannot be opened, do not bypass additional security protections.

Instead, verify the installer checksum and report the error.

## The DMG Will Not Open

If the installer does not mount:

1. Delete the incomplete or failed download.
2. Download the installer again from the official GitHub Releases page.
3. Confirm the download has completed.
4. Try opening the DMG again.

A corrupted or incomplete download may prevent the disk image from mounting.

## Phantom Opens but a Feature Does Not Work

Some workflows require additional processing time, especially when working with high-resolution images or video.

If a feature appears unresponsive:

1. Allow the current operation to finish.
2. Check whether Phantom displays an error.
3. Confirm that the source file is supported.
4. Try a smaller test file.
5. Restart Phantom if necessary.

If the issue persists, report it through GitHub Issues.

Include the affected workflow, relevant error messages, and steps needed to reproduce the problem.

Do not upload private or sensitive media unless you are comfortable sharing it.

## Export Problems

If an export fails:

1. Confirm sufficient free storage is available.
2. Check the selected export destination.
3. Verify that the destination is writable.
4. Confirm that the source media is accessible.
5. Try exporting a short or smaller sample.

If the problem continues, record the error message and report the issue.

## Performance Issues

Performance can vary depending on:

- Mac hardware
- Available memory
- Source media resolution
- Video frame rate
- Processing complexity
- Available storage

High-resolution video processing and frame interpolation can require substantial processing time.

For demanding workflows, close unnecessary applications and ensure sufficient storage is available.

---

# Verify Your Download

For additional security, you can verify that the downloaded installer matches the official release.

## SHA-256 Checksum

**Phantom I v0.7.5 Build 12**

Expected SHA-256:

```text
fb40993d00199c840f929ca5f8c1ad9a9a813c97d5d29383f5c14703342d8b8d
```

To verify your download:

1. Open Terminal.
2. Enter `shasum -a 256` followed by a space.
3. Drag the downloaded DMG file into the Terminal window.
4. Press Return.

For example:

```bash
shasum -a 256 ~/Downloads/Phantom-I-v0.7.5-Build12-Expanded-RC.dmg
```

Compare the resulting checksum with the official value above.

The two values must match exactly.

If they do not match, do not install the application. Download it again from the official repository.

Checksum verification confirms that the file matches the published release artifact. It does not replace Apple's notarisation or other security checks.

---

# Updating Phantom

When a new version becomes available:

1. Visit the official GitHub Releases page.
2. Download the latest DMG.
3. Close Phantom.
4. Open the new installer.
5. Drag the new application into Applications.
6. Replace the existing application when prompted.

Back up important projects before updating.

Release notes will describe significant changes, fixes, and known limitations.

---

# Uninstalling Phantom

To uninstall Phantom:

1. Quit the application.
2. Open Finder.
3. Navigate to Applications.
4. Move `Phantom.app` to the Trash.

This removes the application bundle.

Projects, exported media, and some application data may remain in their original locations.

Do not delete project folders unless you no longer need their contents.

---

# Known Limitations

Phantom I is actively developed.

Current limitations include:

- Some video timeline previews require rendering.
- Video Colour previews may not update continuously.
- Direct multitrack-to-Motion-Blur chaining is not currently supported.
- Some advanced Graphic Design operations remain incomplete.
- Certain complex workflows may require additional processing time.
- The application is not currently Apple-notarised.

These limitations do not necessarily affect every workflow.

Refer to individual release notes for updates and fixes.

---

# Bug Reports and Feedback

Found a bug or have a feature suggestion?

Visit:

https://github.com/dydyktzzn/getphantom/issues

When reporting an issue, please include:

- Phantom version and build
- macOS version
- Mac model
- A description of the issue
- Steps to reproduce it
- Relevant error messages

Screenshots are helpful when they do not contain sensitive information.

Constructive feedback and feature suggestions are welcome.

---

# Official Downloads

Only download Phantom I from the official repository:

**https://github.com/dydyktzzn/getphantom**

Avoid unofficial mirrors or modified installers.

---

## Phantom I

**One application. More creative possibilities.**

Built for macOS.
