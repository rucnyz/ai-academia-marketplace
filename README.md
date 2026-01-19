# AI Academia Marketplace

A Claude Code plugin marketplace for academic and AI research workflows.

## Plugins

### academia-reference

Format academic references into proper BibTeX format.

**Features:**
- Convert arXiv paper URLs/IDs to BibTeX `@article` entries
- Format conference papers (NeurIPS, ICML, ICLR, SOSP, OSDI, ISCA, MLSys, ACL) as `@inproceedings`
- Handle GitHub repositories and URLs as `@misc` entries
- Automatic citation key generation
- Proper author name formatting

## Installation

```bash
# Add the marketplace
/plugin marketplace add yuzhounie/ai-academia-marketplace

# Install a plugin
/plugin install academia-reference@ai-academia-marketplace
```

## Usage

Once installed, use the `reference-formatter` agent:

```
@reference-formatter https://arxiv.org/abs/2308.12950
```

## License

MIT
