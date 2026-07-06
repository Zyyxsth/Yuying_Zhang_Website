# Personalization checklist / 个性化修改清单

This site is based on Academic Pages and has English and Chinese routes. Content from `张钰迎简历.docx` has been imported. Phone and WeChat details are intentionally not published.

## 1. Basic profile / 基本资料

Edit `_config.yml`:

- `title`, `title_zh` (currently Yuying Zhang / 张钰迎)
- `url`, `repository`
- `author` (English sidebar)
- `author_zh` (Chinese sidebar)

The current avatar is `images/profile.svg`. To use a portrait, place it in `images/` and update `author.avatar`.

## 2. Home pages / 中英文主页

- English: `_pages/about.md`
- 中文：`_pages/about-zh.md`
- Projects: `_pages/projects.md`, `_pages/projects-zh.md`

The language switch in the upper-right corner connects these pages.

## 3. Academic content / 学术内容

Create one Markdown file per item in:

- `_publications/` — publications / 论文
- `_talks/` — talks / 学术报告
- `_teaching/` — teaching / 教学

Edit `_pages/cv.md` and `_pages/cv-zh.md` for the two CV pages.

## 4. Local preview / 本地预览

Use Ruby 3 and Bundler:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.
