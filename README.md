# Disney Min-Maxing

Jekyll-powered GitHub Pages site for a Tokyo Disney Resort min-maxing guide.

## Local development

1. Install Ruby and Bundler.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve`.
4. Open `http://127.0.0.1:4000`.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In GitHub, open `Settings` -> `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Select your default branch and `/ (root)`.
5. Save. GitHub Pages will build the Jekyll site automatically.
6. If you rename the repository, update `baseurl` in `_config.yml` to match the exact repo name and casing used in the URL.

## Main files

- `index.md`: homepage content
- `_layouts/default.html`: shared layout
- `assets/css/style.css`: custom styling
- `_config.yml`: Jekyll configuration
