# rime-international

## About

This is a layout for easily writing accented characters commonly used in languages written with the Latin alphabet. For example, you can write `á` by typing `;as`, `à` by typing `;af`, `ã` by typing `;ax`, `ả` by typing `;ar`, `ạ` by typing `;aj`, `ă` by typing `;aw`, `ê` by typing `;ee`, `ü` by typing `;uv`, `ű` by typing `;u;`, `ç` by typing `;c`, `ñ` by typing `;n`, `ấ` by typing `;jaas`, etc (the layout is inspired by TELEX for Vietnamese).

## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/international` using plum:

```bash
bash rime-install gkovacs/international
```

Finally edit `default.custom.yaml` and add `international` to the schema list:

```bash
patch:
  schema_list:
    - schema: international
```

Now reload RIME and it should appear under your layouts.
