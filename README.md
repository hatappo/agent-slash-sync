# ⚠️ This package has been renamed

## agent-slash-sync → agent-command-sync

This package has been renamed to better reflect its functionality.

### New Package Information

📦 **New Package**: [agent-command-sync](https://www.npmjs.com/package/agent-command-sync)
🔗 **GitHub**: [https://github.com/hatappo/agent-command-sync](https://github.com/hatappo/agent-command-sync)
🔧 **New Command**: `acsync` (previously `assync`)

### Installation

```bash
npm uninstall -g agent-slash-sync
npm install -g agent-command-sync
```

### Migration Guide

1. Uninstall the old package: `npm uninstall -g agent-slash-sync`
2. Install the new package: `npm install -g agent-command-sync`
3. Replace `assync` with `acsync` in your scripts and documentation
4. Update any automation or CI/CD pipelines to use the new command

### What's New in v2.0.0

- ✨ Added support for Codex CLI (third tool format)
- 🏗️ Implemented Intermediate Representation (IR) architecture
- 🔄 Changed option from `-d, --dry-run` to `-n, --noop`
- 📝 Improved documentation and error messages

### Breaking Changes

- Package name changed from `agent-slash-sync` to `agent-command-sync`
- Command changed from `assync` to `acsync`
- Option `-d, --dry-run` changed to `-n, --noop`
- Removed `-c, --convert` option; now use `-s, --src` and `-d, --dest`

### Support

For issues and questions, please visit the new repository:
🐛 [Issues](https://github.com/hatappo/agent-command-sync/issues)
📚 [Documentation](https://github.com/hatappo/agent-command-sync#readme)

---

**Note**: This repository is maintained only for migration purposes. All new development happens in the [agent-command-sync](https://github.com/hatappo/agent-command-sync) repository.