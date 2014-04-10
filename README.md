TYPO3.belayout_tsprovider
=========================

example usage, feel free to split in several files

```
backendlayouts {
    Layout1 {
        icon = EXT:themes_gridelements/ext_icon.png
        name = Layout 1
        backend_layout (
            colCount = 3
            rowCount = 5
            rows {
                1 {
                    columns {
                        1 {
                            name = Feature
                            colspan = 3
                            colPos = 3
                        }
                    }
                }
                2 {
                    columns {
                        1 {
                            name = Content
                            colspan = 3
                            rowspan = 3
                            colPos = 0
                        }
                    }
                }
                3 {
                    columns {
                    }
                }
                4 {
                    columns {
                    }
                }
                5 {
                    columns {
                        1 {
                            name = Extended
                            colspan = 3
                            colPos = 4
                        }
                    }
                }
            }
        )
    }
    Layout2 {
        icon = EXT:themes_gridelements/ext_icon.png
        name = Layout 2
        backend_layout (
            colCount = 3
            rowCount = 5
            rows {
                1 {
                    columns {
                        1 {
                            name = Feature
                            colspan = 3
                            colPos = 3
                        }
                    }
                }
                2 {
                    columns {
                        1 {
                            name = Content
                            colspan = 3
                            rowspan = 3
                            colPos = 0
                        }
                    }
                }
                3 {
                    columns {
                    }
                }
                4 {
                    columns {
                    }
                }
                5 {
                    columns {
                        1 {
                            name = Extended
                            colspan = 3
                            colPos = 4
                        }
                    }
                }
            }
        )
    }
}
```
