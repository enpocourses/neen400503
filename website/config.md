<!--
Add here global page variables to use throughout your website.
-->
@def website_title = "新能源热利用"
@def website_descr = "新能源热利用课程网站"
@def website_url   = "https://ai4energy.github.io/neen400503/"
@def title         = "新能源热利用"
@def prepath       = "neen400503"
@def description = """新能源热利用课程网站"""
@def author        = "Mingtao Li"
@def mintoclevel   = 2
@def ignore = ["node_modules/", "franklin", "franklin.pub"]
@def generate_rss = true
@def use_header_img     = true
@def use_hero           = false
@def hero_width         = "80%"
@def hero_margin_top    = "100px"
@def add_github_view  = true
@def add_github_star  = true
@def github_repo      = "ai4energy/neen400503"
@def section_width = 10
@def header_color       = "#3f6388"
@def link_color         = "#2669DD"
@def link_hover_color   = "teal"
@def section_bg_color   = "#f6f8fa"
@def footer_link_color  = "cornflowerblue"
@def highlight_theme    = "atom-one-dark"
@def code_border_radius = "10px"
@def code_output_indent = "15px"
@def sections        = Pair{String,String}[]
@def section_counter = 1
@def showall         = true

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}