# vim-tag-plugin-snippets

This is my collection of markdown snippets for quickly inserting tag plugin snippets for Hexo or Octopress. I use Hexo myself so some of the tag plugins may not be available on Octopress and some Octopress ones may not be available here.

Personally, I use [UltiSnips](https://github.com/SirVer/ultisnips) but I've quickly ported my snippets to the [vim-snipmate](https://github.com/garbas/vim-snipmate) format too. However, I had some issues getting snipmate to work with my other plugins so I didn't get round to testing them out. Please feel free to fork and submit a pull request if they don't work or if you want to add more snippets.

## How to install

I recommend using a plugin manager. Many are available but I use [vim-plug](https://github.com/junegunn/vim-plug)

- Install [SirVer/UltiSnips](https://github.com/SirVer/ultisnips) or [garbas/vim-snipmate](https://github.com/garbas/vim-snipmate)
- Install `greg-js/vim-tag-plugin-snippets`

## Usage

Use the default trigger (tab) or set it to something like CTRL-J with `let g:UltiSnipsExpandTrigger="<c-j>"`. In insert mode, type the trigger and tab or CTRL-J to expand the snippet. Keep tapping expand trigger to move through the expansion, modifying or deleting as you go along. Check the UltiSnips or vim-snipmate docs if this sounds confusing.

