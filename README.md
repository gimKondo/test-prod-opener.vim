# test-prod-opener.vim
## Summary
This is a vim plugin for opening test file from production file, and vice versa.
Currently, this can deal just only Ruby+RSpec and Elixir+ExUnit.

## Setting example

```vim
augroup test-code-util
autocmd FileType ruby nmap <Space>r <Plug>(ruby-spec-prod-open)
autocmd FileType elixir nmap <Space>r <Plug>(elixir-test-prod-open)
augroup END
```

## License
Refer to [here](LICENSE).
