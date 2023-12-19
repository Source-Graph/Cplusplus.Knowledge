# Inspire.
https://www.reddit.com/r/cpp/comments/sbrcx1/comment/hu2z48x/

# Question::
>How do you get auto-completion/suggestion and on-the-fly code analysis in Vim?

Answer:
>use plugins.
>I prefer coc.nvim paired with coc-clangd
>Clangd is what CLion uses under-the-hood for a lot of its autocomplete/linting/etc., so this pair gets you fairly close. (you miss out on CLion's proprietary additions and AI completion, but for quick work or places CLion is too heavy, its great)

# Project:
- https://github.com/neoclide/coc.nvim
- https://github.com/clangd/coc-clangd
