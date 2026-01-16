# Jordan Terry Academic Website

Source code for [jkterry.ai](https://jkterry.ai) - Personal academic website of Dr. Jordan Terry.

## 📝 Content Editing Guide

### Which File to Edit for What:

| Content to Edit | File to Open |
|----------------|--------------|
| **Academic Publications** | `_data/academic.yml` (under `Publications:` section) |
| **Academic Talks** | `_data/academic.yml` (under `Talks:` section) |
| **Teaching Experience** | `_data/academic.yml` (under `Teaching:` section) |
| **CV/Resume Page** | `pages/cv.md` |
| **Site Name & Contact Info** | `_config.yml` |
| **Social Media Links** | `_config.yml` |
| **Academic Works Page Layout** | `pages/academic-works.html` |
| **Home Page Content** | `page/index.md` |
| **Other Website Pages** | `.md` files in `pages/` directory |
| **Site Layout/Templates** | Files in `_layouts/` folder |
| **Reusable Components** | Files in `_includes/` folder |

### Quick Examples:

**To add a new paper:**
1. Open `_data/academic.yml`
2. Add to the `Publications:` list:
```yaml
- title: "Your Paper Title"
  authors: "Coauthor Name, J. K. Terry, Other Author"
  location: "Conference Name"
  date: "2024"
  arxiv: "https://arxiv.org/abs/..."
