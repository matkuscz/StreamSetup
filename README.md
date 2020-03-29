# StreamSetup
How To Setup Stream


# Webovka
Github pages
- jekyll
- aby fakal ve Fedore:
   sudo dnf install redhat-rpm-config
   sudo dnf install ruby ruby-devel @development-tools
   gem install jekyll
   gem install bundler
- projekt v jekyllu
https://jekyllrb.com/docs/step-by-step/01-setup/
- cd projekt
- bundle init
- otevrit "Gemfile" pridat "gem "jekyll""
- spustit "bundle" - nainstaluje dependency projektu
   
- Vytvoreni stranky:
  - vytvorit novou slozku, ta bude root
  - mkdir web
  - cd web
  - edituj index.html
  - build
    - jekyll build - vystup do _site
    - jekyll serve - http://localhost:4000
    - este aby se to vybuildilo musel jsem pridat do systemu nebo Gemfile:
      - gem "jekyll"
      - gem "addressable"
      - gem "public_suffix"
      - gem "colorator"
      
      
     
Funkcni thema:
- jekyll new myblog
- cd myblog
- bundle exec jekyll serve
- add this to gemfile:
  - gem "jekyll-theme-console"
- spustit bundle
- do _config.yml
  - theme: jekyll-theme-console
- spustit bundle update
- spustit "bundle exec jekyll serve"    
  
