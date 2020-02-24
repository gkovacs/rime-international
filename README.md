# rime-international

## About

This is a layout for easily writing accented characters commonly used in languages written with the Latin alphabet. For example, here's some common characters:

* `á` = `;as`
* `à` = `;af`
* `ã` = `;ax`
* `ả` = `;ar`
* `ạ` = `;aj`
* `ă` = `;aw`
* `â` = `;aa`
* `ê` = `;ee`
* `ê` = `;ee`
* `ü` = `;uv`
* `ư` = `;uw`
* `ű` = `;u;`
* `ç` = `;c`
* `ñ` = `;n`
* `ấ` = `;jaas`
* `č` = `;jc`

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
