# Gemfile for managing Ruby project dependencies

# Source from where the system should download Ruby gems (libraries)
source "https://rubygems.org"

# Specifies the version of Jekyll to be used in the project
gem "jekyll", "~> 3.7.3"

# Adds a theme named "jekyll-theme-pirati" to the installation
gem "jekyll-theme-pirati", "7.0.0"

# Provides support for GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Jekyll-specific gems
group :jekyll_plugins do
  # Provides RSS feed for the site
  gem "jekyll-feed", "~> 0.6"
  
  # Adds pagination to posts
  gem "jekyll-paginate"
  
  # Generates a sitemap for the site
  gem "jekyll-sitemap"
  
  # Adds assets functionalities to Jekyll
  gem "jekyll-assets", "3.0.11"
  
  # Allows setting environment variables in development environment
  gem 'jekyll-environment-variables'
end

# Gems used only in development and test environments
group :development, :test do
  # Tests the validity of generated HTML
  gem "html-proofer"
end

# Gems for image manipulation
gem "mini_magick" # Facilitates working with images
gem "image_optim" # Optimizes images for faster site loading
gem "image_optim_bin" # Optional: installs image optimization package
gem "image_optim_pack" # Packages image optimizations

# Gems for JavaScript and CSS processing
gem 'sprockets', '4.0.0.beta8' # Support for assets mechanism in Jekyll
gem 'uglifier', '~> 4.0.0' # Minifies JavaScript
gem "autoprefixer-rails" # Automatically adds vendor prefixes to CSS files

# Additional gems
gem "json" # Used for gem building
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby] # Adds timezone files for specific platforms
gem "wdm", "~> 0.1.1" if Gem.win_platform? # Ensures watch mode works correctly on Windows
