TYPO3.belayout_tsprovider
=========================

example usage, feel free to split in several files
PageTS inclusion:

```
<INCLUDE_TYPOSCRIPT: source="DIR:EXT:themes_gridelements/Configuration/BackendLayouts">
```


PageTS
```
backendlayouts {
    Layout1 {
        icon = EXT:themes_gridelements/ext_icon.png
        name = Layout 1
        backend_layout (
            colCount = 5
            rowCount = 3
            rows {
                1 {
                    columns {
                        1 {
                            name = Feature
                            colspan = 5
                            colPos = 3
                        }
                    }
                }
                2 {
                    columns {
                        1 {
                            name = Sidebar
                            colPos = 2
                        }
                        2 {
                            name = Menu
                            colPos = 1
                        }
                        3 {
                            name = Content
                            colspan = 3
                            colPos = 0
                        }
                    }
                }
                3 {
                    columns {
                        1 {
                            name = Extended
                            colspan = 5
                            colPos = 4
                        }
                    }
                }
            }
        )
    }
}
```
