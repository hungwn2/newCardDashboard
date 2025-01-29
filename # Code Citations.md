# Code Citations

## License: unknown
https://github.com/GiovaniPM/Help/tree/86abac85521d3e09a44cf32527c15d68cc4cbd75/python/CustomTkinter-master/customtkinter/windows/widgets/theme/theme_manager.py

```
{}  # contains all the theme data
    _built_in_themes: List[str] = ["blue", "green", "dark-blue", "sweetkind"]
    _currently_loaded_theme: Union[str, None] = None

    @classmethod
    def load_theme(cls, theme_name_or_path: str)
```


## License: unknown
https://github.com/tarngaina/LtMAO/tree/dd31e36a47afabfd2e4b5bb00d39e6ca60a81940/LtMAO/pyembed/Lib/site-packages/customtkinter/windows/widgets/theme/theme_manager.py

```
Union

class ThemeManager:

    theme: dict = {}  # contains all the theme data
    _built_in_themes: List[str] = ["blue", "green", "dark-blue", "sweetkind"]
    _currently_loaded_theme: Union[str, None] = None

    @classmethod
    def
```


## License: MIT
https://github.com/TomSchimansky/CustomTkinter/tree/aaa1ba1cbb54cb5dc04401f327d158e238a5fb86/customtkinter/windows/widgets/theme/theme_manager.py

```
"]
                    else:
                        cls.theme[key] = cls.theme[key]["Linux"]

            # fix name inconsistencies
            if "CTkCheckbox" in cls.theme.keys():
                cls.theme["CTkCheckBox"] = cls.theme.pop("
```


## License: unknown
https://github.com/vidal-root/BotWhatsPywhatkit/tree/a1ca3554de38e0a2fa0ddb5f2c3dcca3919e2ba5/venv/Lib/site-packages/customtkinter/windows/widgets/theme/theme_manager.py

```
.platform.startswith("win"):
                        cls.theme[key] = cls.theme[key]["Windows"]
                    else:
                        cls.theme[key] = cls.theme[key]["Linux"]

            # fix name inconsistencies
            if "CTkCheckbox
```

