# vscode-parsec-snippets

## Features

This plugin provides snippets with the basic usage syntax for the most used components of Parsec Next.

All you need to do is typing the component's name **all in lowercase** and press tab. (all components will follow this logic).

``` html
pbtnd + [tab] =>
<parsec-btn-dropdown
  :label="$t('')"
  :options="options"
  @item-click=""
>
  <template #option-toolbar="{option}">"
    <parsec-icon
      name="icon-"
      @click.stop="() => func(option)"
      :label="$t('')"
    />
  </template>
</parsec-btn-dropdown>
```
