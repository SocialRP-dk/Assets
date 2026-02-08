# Assets

A public repository for hosting images and other static assets used across SocialRP-dk projects.

## Purpose

This repository serves as a centralized location for storing and serving images that can be referenced by other projects, websites, and applications.

## Usage

### Accessing Images

Images in this repository can be accessed directly via GitHub's raw content URL:

```
https://raw.githubusercontent.com/SocialRP-dk/Assets/main/images/<filename>
```

### Example

```html
<img src="https://raw.githubusercontent.com/SocialRP-dk/Assets/main/images/logo.png" alt="Logo">
```

Or in Markdown:

```markdown
![Logo](https://raw.githubusercontent.com/SocialRP-dk/Assets/main/images/logo.png)
```

## Directory Structure

```
/images         - General images
/icons          - Icon files
/logos          - Logo files
/backgrounds    - Background images
```

## Contributing

When adding new assets:

1. Place files in the appropriate directory
2. Use descriptive, lowercase filenames with hyphens (e.g., `user-avatar.png`)
3. Optimize images before uploading to keep repository size manageable
4. Avoid uploading unnecessarily large files

## License

See [LICENSE](LICENSE) file for details.