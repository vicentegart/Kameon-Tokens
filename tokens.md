# Tokens

```json
// Some code
{
  "global": {
    "colors": {
      "system": {
        "primary": {
          "value": "{colors.blue-500}",
          "type": "color"
        },
        "tertiary": {
          "value": "{colors.black-400}",
          "type": "color"
        },
        "secondary": {
          "value": "{colors.black-500}",
          "type": "color"
        },
        "success": {
          "value": "#53A451",
          "type": "color"
        },
        "error": {
          "value": "#B00020",
          "type": "color"
        },
        "warning": {
          "value": "#DD8D1A",
          "type": "color"
        },
        "info": {
          "value": "#2195F2",
          "type": "color"
        },
        "page-background": {
          "value": "#FAFAFA",
          "type": "color"
        },
        "inactive": {
          "value": "#92999B",
          "type": "color"
        },
        "surface": {
          "value": "{colors.white}",
          "type": "color"
        },
        "on-secondary": {
          "value": "{colors.white}",
          "type": "color"
        },
        "on-primary": {
          "value": "{colors.white}",
          "type": "color"
        },
        "on-tertiary": {
          "value": "{colors.white}",
          "type": "color"
        },
        "on-status": {
          "value": "{colors.white}",
          "type": "color"
        }
      },
      "blue-900": {
        "value": "#0E66E8",
        "type": "color"
      },
      "blue-800": {
        "value": "#1678EC",
        "type": "color"
      },
      "blue-700": {
        "value": "#1A82EE",
        "type": "color"
      },
      "blue-600": {
        "value": "#1D8DF0",
        "type": "color"
      },
      "blue-500": {
        "value": "#2195F2",
        "type": "color"
      },
      "blue-300": {
        "value": "#65B5F6",
        "type": "color"
      },
      "blue-400": {
        "value": "#44A5F4",
        "type": "color"
      },
      "blue-200": {
        "value": "#91CAF9",
        "type": "color"
      },
      "blue-100": {
        "value": "#BEDFFB",
        "type": "color"
      },
      "blue-050": {
        "value": "#E5F2FD",
        "type": "color"
      },
      "black-900": {
        "value": "#0D1317",
        "type": "color"
      },
      "black-800": {
        "value": "#161F22",
        "type": "color"
      },
      "black-700": {
        "value": "#1B262A",
        "type": "color"
      },
      "black-600": {
        "value": "#212D30",
        "type": "color"
      },
      "black-500": {
        "value": "#253236",
        "type": "color"
      },
      "black-400": {
        "value": "#465154",
        "type": "color"
      },
      "black-300": {
        "value": "#667072",
        "type": "color"
      },
      "black-200": {
        "value": "#92999B",
        "type": "color"
      },
      "black-100": {
        "value": "#BEC2C3",
        "type": "color"
      },
      "black-050": {
        "value": "#E5E6E7",
        "type": "color"
      },
      "black-020": {
        "value": "#F2F3F3",
        "type": "color"
      },
      "white": {
        "value": "#ffffff",
        "type": "color"
      }
    },
    "card": {
      "border-color": {
        "value": "{colors.black-050}",
        "type": "color"
      },
      "background-color": {
        "value": "{colors.system.surface}",
        "type": "color"
      },
      "border-width": {
        "value": "1",
        "type": "borderWidth"
      },
      "content-area": {
        "inner-divider": {
          "value": {
            "x": "0",
            "y": "1",
            "blur": "0",
            "spread": "0",
            "color": "{colors.black-050}",
            "type": "innerShadow"
          },
          "type": "boxShadow"
        }
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      }
    },
    "info-block": {
      "tip-icon-color": {
        "value": "{colors.black-200}",
        "type": "color"
      },
      "label-color": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "title-color": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "label-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title case"
        },
        "type": "typography"
      },
      "title-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-medium}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title case"
        },
        "type": "typography"
      }
    },
    "system": {
      "font-family": {
        "value": "Roboto",
        "type": "fontFamilies"
      }
    },
    "space-xxx-sm": {
      "value": "4",
      "type": "spacing"
    },
    "text-uc": {
      "value": "uppercase",
      "type": "textCase"
    },
    "font": {
      "size-xx-sm": {
        "value": "10",
        "type": "fontSizes"
      },
      "size-x-sm": {
        "value": "12",
        "type": "fontSizes"
      },
      "size-sm": {
        "value": "14",
        "type": "fontSizes"
      },
      "size-md": {
        "value": "16",
        "type": "fontSizes"
      },
      "size-lg": {
        "value": "20",
        "type": "fontSizes"
      },
      "size-x-lg": {
        "value": "24",
        "type": "fontSizes"
      },
      "size-xx-lg": {
        "value": "32",
        "type": "fontSizes"
      },
      "size-xxx-lg": {
        "value": "48",
        "type": "fontSizes"
      },
      "size-xxxx-lg": {
        "value": "60",
        "type": "fontSizes"
      },
      "weight-light": {
        "value": "Light",
        "type": "fontWeights"
      },
      "weight-regular": {
        "value": "Regular",
        "type": "fontWeights"
      },
      "weight-medium": {
        "value": "Medium",
        "type": "fontWeights"
      },
      "weight-bold": {
        "value": "Bold",
        "type": "fontWeights"
      },
      "line-height-xx-sm": {
        "value": "10",
        "type": "lineHeights"
      },
      "line-height-x-sm": {
        "value": "12",
        "type": "lineHeights"
      },
      "line-height-sm": {
        "value": "14",
        "type": "lineHeights"
      },
      "line-height-md": {
        "value": "16",
        "type": "lineHeights"
      },
      "line-height-lg": {
        "value": "20",
        "type": "lineHeights"
      },
      "line-height-x-lg": {
        "value": "24",
        "type": "lineHeights"
      },
      "line-height-xx-lg": {
        "value": "32",
        "type": "lineHeights"
      },
      "line-height-xxx-lg": {
        "value": "48",
        "type": "lineHeights"
      },
      "line-height-xxxx-lg": {
        "value": "60",
        "type": "lineHeights"
      }
    },
    "space-xx-sm": {
      "value": "8",
      "type": "spacing"
    },
    "space-x-sm": {
      "value": "12",
      "type": "spacing"
    },
    "space-sm": {
      "value": "16",
      "type": "spacing"
    },
    "space-md": {
      "value": "20",
      "type": "spacing"
    },
    "space-lg": {
      "value": "24",
      "type": "spacing"
    },
    "space-x-lg": {
      "value": "28",
      "type": "spacing"
    },
    "space-xx-lg": {
      "value": "32",
      "type": "spacing"
    },
    "space-xxx-lg": {
      "value": "36",
      "type": "spacing"
    },
    "space-xxxx-lg": {
      "value": "52",
      "type": "spacing"
    },
    "size": {
      "x-sm": {
        "value": "12",
        "type": "sizing"
      },
      "sm": {
        "value": "16",
        "type": "sizing"
      },
      "md": {
        "value": "20",
        "type": "sizing"
      },
      "lg": {
        "value": "24",
        "type": "sizing"
      },
      "x-lg": {
        "value": "28px",
        "type": "sizing"
      },
      "xx-lg": {
        "value": "32px",
        "type": "sizing"
      },
      "xxx-lg": {
        "value": "40px",
        "type": "sizing"
      },
      "xxxx-lg": {
        "value": "48px",
        "type": "sizing"
      }
    },
    "radii": {
      "pill": {
        "value": "120",
        "type": "borderRadius",
        "description": "Buttons, tags, tabs, and similar."
      },
      "default": {
        "value": "8",
        "description": "Inputs, textareas, and similar",
        "type": "borderRadius"
      },
      "circle": {
        "value": "999",
        "description": "avatars",
        "type": "borderRadius"
      }
    },
    "button": {
      "small": {
        "icon-left": {
          "margin-right": {
            "value": "{space-xx-sm}",
            "type": "spacing"
          },
          "padding-left": {
            "value": "{space-sm}",
            "type": "spacing"
          }
        },
        "icon-right": {
          "padding-right": {
            "value": "{space-sm}",
            "type": "spacing"
          },
          "margin-left": {
            "value": "{space-xx-sm}",
            "type": "spacing"
          }
        },
        "padding-left": {
          "value": "{space-lg}",
          "type": "spacing"
        },
        "padding-right": {
          "value": "{space-lg}",
          "type": "spacing"
        },
        "padding-top": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        },
        "padding-bottom": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        },
        "label-typo": {
          "value": {
            "fontFamily": "{system.font-family}",
            "fontWeight": "{font.weight-regular}",
            "lineHeight": "{font.line-height-lg}",
            "fontSize": "{font.size-md}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "Title"
          },
          "type": "typography"
        },
        "iconfont-typo": {
          "value": {
            "fontFamily": "{icon.font-family}",
            "fontWeight": "{font.weight-light}",
            "lineHeight": "AUTO",
            "fontSize": "{icon.font-size.small}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "none"
          },
          "type": "typography"
        }
      },
      "medium": {
        "icon-right": {
          "margin-left": {
            "value": "{space-x-sm}",
            "type": "spacing"
          },
          "padding-right": {
            "value": "{space-lg}",
            "type": "spacing"
          }
        },
        "icon-left": {
          "padding-left": {
            "value": "{space-lg}",
            "type": "spacing"
          },
          "margin-right": {
            "value": "{space-x-sm}",
            "type": "spacing"
          }
        },
        "padding-left": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        },
        "padding-right": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        },
        "padding-top": {
          "value": "{space-x-sm}",
          "type": "spacing"
        },
        "padding-bottom": {
          "value": "{space-x-sm}",
          "type": "spacing"
        },
        "label-typo": {
          "value": {
            "fontFamily": "{system.font-family}",
            "fontWeight": "{font.weight-regular}",
            "lineHeight": "{font.line-height-x-lg}",
            "fontSize": "{font.size-lg}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "Title"
          },
          "type": "typography"
        },
        "iconfont-typo": {
          "value": {
            "fontFamily": "{icon.font-family}",
            "fontWeight": "{font.weight-light}",
            "lineHeight": "AUTO",
            "fontSize": "{icon.font-size.medium}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "none"
          },
          "type": "typography"
        }
      },
      "border-color-focus": {
        "value": "{colors.blue-100}",
        "type": "color"
      },
      "border-width": {
        "value": "1",
        "type": "borderWidth"
      },
      "border-radii": {
        "value": "{radii.pill}",
        "type": "borderRadius"
      },
      "filled": {
        "on-surface": {
          "label-color": {
            "value": "{colors.system.on-primary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-primary}",
            "type": "color"
          },
          "color": {
            "value": "{colors.system.primary}",
            "type": "color"
          },
          "color-hovered": {
            "value": "rgba({colors.system.primary}, 0.7)",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.primary}, 0.5)",
            "type": "color"
          },
          "color-disabled": {
            "value": "rgba({colors.system.primary}, 0.3)",
            "type": "color"
          }
        },
        "on-secondary": {
          "label-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "color-hovered": {
            "value": "rgba({colors.system.on-secondary}, 0.7)",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.on-secondary}, 0.5)",
            "type": "color"
          },
          "color-disabled": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-tertiary": {
          "label-color": {
            "value": "{colors.system.tertiary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.tertiary}",
            "type": "color"
          },
          "color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "color-hovered": {
            "value": "rgba({colors.system.on-tertiary}, 0.7)",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.on-tertiary}, 0.5)",
            "type": "color"
          },
          "color-disabled": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          }
        }
      },
      "outlined": {
        "on-surface": {
          "label-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "border-color": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.secondary}, 0.1)",
            "type": "color"
          },
          "border-color-disabled": {
            "value": "rgba({colors.system.secondary}, 0.1)",
            "type": "color"
          },
          "label-color-disabled": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          },
          "icon-color-disabled": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-secondary": {
          "label-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "border-color": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.on-secondary}, 0.1)",
            "type": "color"
          },
          "border-color-disabled": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          },
          "label-color-disabled": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          },
          "icon-color-disabled": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-tertiary": {
          "label-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "border-color": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.on-tertiary}, 0.1)",
            "type": "color"
          },
          "border-color-disabled": {
            "value": "rgba({colors.system.on-tertiary}, 0.1)",
            "type": "color"
          },
          "label-color-disabled": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          },
          "icon-color-disabled": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          }
        }
      },
      "text": {
        "on-surface": {
          "label-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color-hovered": {
            "value": "{colors.system.primary}",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.primary}",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.secondary}, 0.1)",
            "type": "color"
          },
          "label-color-disabled": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          },
          "icon-color-disabled": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-secondary": {
          "label-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "rgba({colors.system.on-secondary}, 0.7)",
            "type": "color"
          },
          "icon-color-hovered": {
            "value": "rgba({colors.system.on-secondary}, 0.7)",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.on-secondary}, 0.1)",
            "type": "color"
          },
          "label-color-disabled": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          },
          "icon-color-disabled": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-tertiary": {
          "label-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "rgba({colors.system.on-tertiary}, 0.7)",
            "type": "color"
          },
          "icon-color-hovered": {
            "value": "rgba({colors.system.on-tertiary}, 0.7)",
            "type": "color"
          },
          "color-pressed": {
            "value": "rgba({colors.system.on-tertiary}, 0.1)",
            "type": "color"
          },
          "label-color-disabled": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          },
          "icon-color-disabled": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          }
        }
      }
    },
    "toast": {
      "icon-color": {
        "value": "{colors.system.on-status}",
        "type": "color"
      },
      "text-color": {
        "value": "{colors.system.on-status}",
        "type": "color"
      },
      "background-color-warning": {
        "value": "{colors.system.warning}",
        "type": "color"
      },
      "background-color-error": {
        "value": "{colors.system.error}",
        "type": "color"
      },
      "background-color-info": {
        "value": "{colors.system.info}",
        "type": "color"
      },
      "background-color-success": {
        "value": "{colors.system.success}",
        "type": "color"
      },
      "icon-leading": {
        "margin-right": {
          "value": "{space-x-sm}",
          "type": "spacing"
        }
      },
      "icon-trailing": {
        "margin-left": {
          "value": "{space-lg}",
          "type": "spacing"
        }
      },
      "paddings": {
        "value": "{space-x-sm}",
        "type": "spacing"
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      },
      "text-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title case"
        },
        "type": "typography"
      }
    },
    "surface": {
      "color": {
        "value": "{colors.white}",
        "type": "color"
      }
    },
    "header": {
      "card": {
        "heading-color": {
          "value": "{colors.system.secondary}",
          "type": "color"
        },
        "subline-color": {
          "value": "{colors.system.secondary}",
          "type": "color"
        },
        "heading-typo": {
          "value": {
            "fontFamily": "{system.font-family}",
            "fontWeight": "{font.weight-bold}",
            "lineHeight": "{font.line-height-lg}",
            "fontSize": "{font.size-lg}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "Title"
          },
          "type": "typography"
        }
      },
      "padding-left": {
        "value": "{space-xx-lg}",
        "type": "spacing"
      },
      "padding-right": {
        "value": "{space-xx-lg}",
        "type": "spacing"
      },
      "padding-top": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "padding-bottom": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "heading-block": {
        "stack": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        }
      },
      "status-block": {
        "margin-left": {
          "value": "{space-lg}",
          "type": "spacing"
        }
      },
      "page": {
        "heading-typo": {
          "value": {
            "fontFamily": "{system.font-family}",
            "fontWeight": "{font.weight-medium}",
            "lineHeight": "{font.line-height-x-lg}",
            "fontSize": "{font.size-x-lg}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "Title"
          },
          "type": "typography"
        },
        "heading-color": {
          "value": "{colors.system.on-tertiary}",
          "type": "color"
        },
        "subline-color": {
          "value": "{colors.system.on-tertiary}",
          "type": "color"
        },
        "container-color": {
          "value": "{colors.system.tertiary}",
          "type": "color"
        }
      },
      "subline-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-sm}",
          "fontSize": "{font.size-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      }
    },
    "input-group": {
      "inset": {
        "value": "{space-x-lg}",
        "type": "spacing"
      },
      "stack": {
        "value": "{space-xxx-lg}",
        "type": "spacing"
      }
    },
    "input": {
      "icon-leading": {
        "margin-right": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        },
        "margin-left": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        }
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      },
      "label-color": {
        "value": "rgba({colors.system.secondary}, 0.7)",
        "type": "color"
      },
      "text-color": {
        "value": "rgba({colors.system.secondary}, 0.7)",
        "type": "color"
      },
      "icon-color": {
        "value": "rgba({colors.system.secondary}, 0.7)",
        "type": "color"
      },
      "help-color": {
        "value": "rgba({colors.system.secondary}, 0.7)",
        "type": "color"
      },
      "symbols-color": {
        "value": "rgba({colors.system.secondary}, 0.7)",
        "type": "color"
      },
      "border-color": {
        "value": "rgba({colors.system.secondary}, 0.3)",
        "type": "color"
      },
      "icon-color-focused": {
        "value": "{colors.system.secondary}",
        "type": "color"
      },
      "text-color-focused": {
        "value": "{colors.system.secondary}",
        "type": "color"
      },
      "label-color-focused": {
        "value": "{colors.system.secondary}",
        "type": "color"
      },
      "border-color-focused": {
        "value": "{colors.system.primary}",
        "type": "color"
      },
      "label-color-error": {
        "value": "{colors.system.error}",
        "type": "color"
      },
      "border-color-error": {
        "value": "{colors.system.error}",
        "type": "color"
      },
      "label-color-hovered": {
        "value": "{colors.system.secondary}",
        "type": "color"
      },
      "border-color-hovered": {
        "value": "{colors.system.secondary}",
        "type": "color"
      },
      "border-color-disabled": {
        "value": "rgba({colors.system.secondary}, 0.1)",
        "type": "color"
      },
      "label-color-disabled": {
        "value": "rgba({colors.system.secondary}, 0.3)",
        "type": "color"
      },
      "icon-color-disabled": {
        "value": "rgba({colors.system.secondary}, 0.3)",
        "type": "color"
      },
      "text-color-disabled": {
        "value": "rgba({colors.system.secondary}, 0.3)",
        "type": "color"
      },
      "help-color-disabled": {
        "value": "rgba({colors.system.secondary}, 0.3)",
        "type": "color"
      },
      "symbols-color-disabled": {
        "value": "rgba({colors.system.secondary}, 0.3)",
        "type": "color"
      },
      "border-width": {
        "value": "1",
        "type": "borderWidth"
      },
      "paddings": {
        "value": "{space-sm}",
        "type": "spacing"
      },
      "help": {
        "paddings-left": {
          "value": "{space-sm}",
          "type": "spacing"
        },
        "paddings-right": {
          "value": "{space-sm}",
          "type": "spacing"
        },
        "paddings-top": {
          "value": "{space-xxx-sm}",
          "type": "spacing"
        }
      },
      "label-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title case"
        },
        "type": "typography"
      },
      "text-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-x-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      },
      "help-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-md}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      },
      "iconfont-typo": {
        "value": {
          "fontFamily": "{icon.font-family}",
          "fontWeight": "{font.weight-light}",
          "lineHeight": "AUTO",
          "fontSize": "{icon.font-size.small}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      }
    },
    "textarea": {
      "text-color": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "label-color": {
        "value": "{colors.black-300}",
        "type": "color"
      },
      "text-color-default": {
        "value": "{colors.black-300}",
        "type": "color"
      },
      "border-color-default": {
        "value": "{colors.black-300}",
        "type": "color"
      },
      "help-color-default": {
        "value": "{colors.black-300}",
        "type": "color"
      },
      "text-color-selected": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "border-color-selected": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "help-color-selected": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "help-color-focused": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "text-color-focused": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "border-color-focused": {
        "value": "{colors.blue-500}",
        "type": "color"
      },
      "text-color-error": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "help-color-error": {
        "value": "{colors.system.error}",
        "type": "color"
      },
      "border-color-error": {
        "value": "{colors.system.error}",
        "type": "color"
      },
      "label-color-disabled": {
        "value": "{colors.black-100}",
        "type": "color"
      },
      "text-color-disabled": {
        "value": "{colors.black-100}",
        "type": "color"
      },
      "border-color-disabled": {
        "value": "{colors.black-100}",
        "type": "color"
      },
      "help-color-disabled": {
        "value": "{colors.black-100}",
        "type": "color"
      },
      "label-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title case"
        },
        "type": "typography"
      },
      "text-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-x-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      },
      "help-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-md}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      }
    },
    "filter": {
      "label-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-x-sm}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title"
        },
        "type": "typography"
      },
      "iconfont-typo": {
        "value": {
          "fontFamily": "{icon.font-family}",
          "fontWeight": "{font.weight-light}",
          "lineHeight": "AUTO",
          "fontSize": "{icon.font-size.x-small}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      },
      "inactive": {
        "on-surface": {
          "label-color": {
            "value": "rgba({colors.system.secondary}, 0.7)",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "border-color": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "{colors.system.secondary}",
            "type": "color"
          }
        },
        "on-secondary": {
          "border-color": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "label-color": {
            "value": "rgba({colors.system.on-secondary}, 0.7)",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          }
        },
        "on-tertiary": {
          "border-color": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "label-color": {
            "value": "rgba({colors.system.on-tertiary}, 0.7)",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          }
        },
        "padding-left": {
          "value": "{space-sm}",
          "type": "spacing"
        },
        "padding-right": {
          "value": "{space-sm}",
          "type": "spacing"
        },
        "padding-top": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        },
        "padding-bottom": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        }
      },
      "active": {
        "on-surface": {
          "label-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "border-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "rgba({colors.system.secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-secondary": {
          "label-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "border-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "rgba({colors.system.on-secondary}, 0.3)",
            "type": "color"
          }
        },
        "on-tertiary": {
          "label-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "border-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "border-color-hovered": {
            "value": "rgba({colors.system.on-tertiary}, 0.3)",
            "type": "color"
          }
        },
        "icon-margin-right": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        },
        "padding-left": {
          "value": "{space-x-sm}",
          "type": "spacing"
        },
        "padding-right": {
          "value": "{space-sm}",
          "type": "spacing"
        }
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      }
    },
    "counter": {
      "text-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-medium}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Uppercase"
        },
        "type": "typography"
      },
      "text-color": {
        "value": "{colors.system.on-status}",
        "type": "color"
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      },
      "base-size": {
        "value": "{size.xxx-lg}",
        "type": "sizing"
      },
      "base-color": {
        "value": "{colors.system.error}",
        "type": "color"
      }
    },
    "info-icon": {
      "initials-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-medium}",
          "lineHeight": "{font.line-height-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title case"
        },
        "type": "typography"
      },
      "initials-text-color": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "background-color": {
        "value": "{colors.black-050}",
        "type": "color"
      },
      "icon-color": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "border-radii": {
        "value": "{radii.circle}",
        "type": "borderRadius"
      },
      "base-size": {
        "value": "{size.xxx-lg}",
        "type": "sizing"
      }
    },
    "tab": {
      "label-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-regular}",
          "lineHeight": "{font.line-height-x-lg}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      },
      "iconfont-typo": {
        "value": {
          "fontFamily": "{icon.font-family}",
          "fontWeight": "{font.weight-light}",
          "lineHeight": "AUTO",
          "fontSize": "{icon.font-size.small}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "none"
        },
        "type": "typography"
      },
      "on-surface": {
        "indicator": {
          "value": {
            "x": "0",
            "y": "-4",
            "blur": "0",
            "spread": "0",
            "color": "{colors.system.primary}",
            "type": "innerShadow"
          },
          "type": "boxShadow"
        },
        "active": {
          "label-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color": {
            "value": "{colors.system.secondary}",
            "type": "color"
          }
        },
        "inactive": {
          "label-color": {
            "value": "rgba({colors.system.secondary}, 0.5)",
            "type": "color"
          },
          "icon-color": {
            "value": "rgba({colors.system.secondary}, 0.5)",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.secondary}",
            "type": "color"
          },
          "icon-color-hovered": {
            "value": "{colors.system.secondary}",
            "type": "color"
          }
        },
        "color-pressed": {
          "value": "{colors.black-050}",
          "type": "color"
        },
        "indicator-color": {
          "value": "{colors.system.primary}",
          "type": "color"
        }
      },
      "on-secondary": {
        "indicator": {
          "value": {
            "x": "0",
            "y": "-4",
            "blur": "0",
            "spread": "0",
            "color": "{colors.system.on-secondary}",
            "type": "innerShadow"
          },
          "type": "boxShadow"
        },
        "active": {
          "icon-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "label-color": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          }
        },
        "inactive": {
          "label-color": {
            "value": "rgba({colors.system.on-secondary}, 0.5)",
            "type": "color"
          },
          "icon-color": {
            "value": "rgba({colors.system.on-secondary}, 0.5)",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          },
          "icon-color-hovered": {
            "value": "{colors.system.on-secondary}",
            "type": "color"
          }
        },
        "color-pressed": {
          "value": "rgba({colors.system.on-secondary}, 0.1)",
          "type": "color"
        },
        "indicator-color": {
          "value": "{colors.system.on-secondary}",
          "type": "color"
        }
      },
      "on-tertiary": {
        "indicator": {
          "value": {
            "x": "0",
            "y": "-4",
            "blur": "0",
            "spread": "0",
            "color": "{colors.system.on-tertiary}",
            "type": "innerShadow"
          },
          "type": "boxShadow"
        },
        "active": {
          "icon-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "label-color": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          }
        },
        "inactive": {
          "icon-color": {
            "value": "rgba({colors.system.on-tertiary}, 0.5)",
            "type": "color"
          },
          "label-color": {
            "value": "rgba({colors.system.on-tertiary}, 0.5)",
            "type": "color"
          },
          "label-color-hovered": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          },
          "icon-color-hovered": {
            "value": "{colors.system.on-tertiary}",
            "type": "color"
          }
        },
        "color-pressed": {
          "value": "rgba({colors.system.on-tertiary}, 0.1)",
          "type": "color"
        },
        "indicator-color": {
          "value": "{colors.system.on-tertiary}",
          "type": "color"
        }
      },
      "icon-left": {
        "margin-right": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        }
      },
      "icon-right": {
        "margin-left": {
          "value": "{space-xx-sm}",
          "type": "spacing"
        }
      },
      "padding-left": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "padding-right": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "padding-top": {
        "value": "{space-sm}",
        "type": "spacing"
      },
      "padding-bottom": {
        "value": "{space-sm}",
        "type": "spacing"
      },
      "on-page": {
        "container-color": {
          "value": "{colors.system.tertiary}",
          "type": "color"
        },
        "container-padding-left": {
          "value": "{space-lg}",
          "type": "spacing"
        },
        "container-padding-right": {
          "value": "{space-lg}",
          "type": "spacing"
        },
        "container-padding-top": {
          "value": "{space-lg}",
          "type": "spacing"
        }
      },
      "on-card": {
        "container-color": {
          "value": "{colors.system.surface}",
          "type": "color"
        },
        "container-padding-left": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        },
        "container-padding-right": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        },
        "container-padding-top": {
          "value": "{space-lg}",
          "type": "spacing"
        }
      }
    },
    "page-info": {
      "overlay": {
        "subtitle-typo": {
          "value": {
            "fontFamily": "{system.font-family}",
            "fontWeight": "{font.weight-medium}",
            "lineHeight": "{font.line-height-x-lg}",
            "fontSize": "{font.size-md}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "none"
          },
          "type": "typography"
        },
        "content-area": {
          "paddings": {
            "value": "{space-lg}",
            "type": "spacing"
          },
          "stack": {
            "value": "{space-xx-lg}",
            "type": "spacing"
          }
        },
        "text-color": {
          "value": "{colors.black-500}",
          "type": "color"
        },
        "icon-color": {
          "value": "{colors.black-500}",
          "type": "color"
        }
      }
    },
    "data-item": {
      "inner-divider": {
        "value": {
          "x": "0",
          "y": "-1",
          "blur": "0",
          "spread": "0",
          "color": "{colors.black-050}",
          "type": "innerShadow"
        },
        "type": "boxShadow"
      },
      "paddings-bottom": {
        "value": "{space-x-sm}",
        "type": "spacing"
      },
      "paddings-top": {
        "value": "{space-x-sm}",
        "type": "spacing"
      },
      "paddings-right": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "paddings-left": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "background-color": {
        "value": "{surface.color}",
        "type": "color"
      }
    },
    "table": {
      "header": {
        "inner-divider": {
          "value": {
            "x": "0",
            "y": "-1",
            "blur": "0",
            "spread": "0",
            "color": "{colors.black-050}",
            "type": "innerShadow"
          },
          "type": "boxShadow"
        },
        "labels-typo": {
          "value": {
            "fontFamily": "{system.font-family}",
            "fontWeight": "{font.weight-light}",
            "lineHeight": "AUTO",
            "fontSize": "{icon.font-size.x-small}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "Title"
          },
          "type": "typography"
        }
      },
      "item": {
        "inner-divider": {
          "value": {
            "x": "0",
            "y": "-1",
            "blur": "0",
            "spread": "0",
            "color": "{colors.black-050}",
            "type": "innerShadow"
          },
          "type": "boxShadow"
        }
      },
      "item-paddings": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "header-paddings": {
        "value": "{space-lg}",
        "type": "spacing"
      },
      "footer-margin-top": {
        "value": "{space-xx-lg}",
        "type": "spacing"
      }
    },
    "badge": {
      "paddings-top": {
        "value": "{space-xx-sm}",
        "type": "spacing"
      },
      "paddings-bottom": {
        "value": "{space-xx-sm}",
        "type": "spacing"
      },
      "paddings-left": {
        "value": "{space-x-sm}",
        "type": "spacing"
      },
      "paddings-right": {
        "value": "{space-x-sm}",
        "type": "spacing"
      },
      "status": {
        "text-color": {
          "value": "{colors.system.on-status}",
          "type": "color"
        },
        "background-color-warning": {
          "value": "{colors.system.warning}",
          "type": "color"
        },
        "background-color-error": {
          "value": "{colors.system.error}",
          "type": "color"
        },
        "background-color-info": {
          "value": "{colors.system.info}",
          "type": "color"
        },
        "background-color-success": {
          "value": "{colors.system.success}",
          "type": "color"
        },
        "background-color-inactive": {
          "value": "{colors.system.inactive}",
          "type": "color"
        }
      },
      "text-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-bold}",
          "lineHeight": "{font.size-x-sm}",
          "fontSize": "{font.size-x-sm}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Uppercase"
        },
        "type": "typography"
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      }
    },
    "action-block": {
      "inset": {
        "value": "{space-md}",
        "type": "spacing"
      }
    },
    "subgroup": {
      "heading-typo": {
        "value": {
          "fontFamily": "{system.font-family}",
          "fontWeight": "{font.weight-bold}",
          "lineHeight": "{font.line-height-md}",
          "fontSize": "{font.size-md}",
          "letterSpacing": "0%",
          "paragraphSpacing": "0",
          "textDecoration": "none",
          "textCase": "Title"
        },
        "type": "typography"
      },
      "heading-color": {
        "value": "{colors.black-500}",
        "type": "color"
      },
      "padding-top": {
        "value": "{space-x-sm}",
        "type": "spacing"
      }
    },
    "group-panel": {
      "content-paddings": {
        "value": "{space-xx-lg}",
        "type": "spacing"
      },
      "content-stack": {
        "value": "{space-xxx-lg}",
        "type": "spacing"
      }
    },
    "modal": {
      "content-area": {
        "paddings": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        }
      },
      "action-panel": {
        "padding-left": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        },
        "padding-right": {
          "value": "{space-xx-lg}",
          "type": "spacing"
        },
        "padding-top": {
          "value": "{space-md}",
          "type": "spacing"
        },
        "padding-bottom": {
          "value": "{space-md}",
          "type": "spacing"
        }
      },
      "border-radii": {
        "value": "{radii.default}",
        "type": "borderRadius"
      }
    },
    "overlay": {
      "shadow": {
        "value": {
          "x": "0",
          "y": "12",
          "blur": "64",
          "spread": "0",
          "color": "{overlay.shadow-color}",
          "type": "dropShadow"
        },
        "type": "boxShadow"
      },
      "filter": {
        "content-area": {
          "paddings": {
            "value": "{space-xx-lg}",
            "type": "spacing"
          },
          "stack": {
            "value": "{space-xxx-lg}",
            "type": "spacing"
          }
        },
        "input-group": {
          "inset": {
            "value": "{space-x-lg}",
            "type": "spacing"
          }
        }
      },
      "column": {
        "content-area": {
          "paddings": {
            "value": "{space-xx-lg}",
            "type": "spacing"
          },
          "stack": {
            "value": "{space-xxx-lg}",
            "type": "spacing"
          }
        },
        "input-group": {
          "inset": {
            "value": "{space-x-lg}",
            "type": "spacing"
          }
        },
        "drag-icon": {
          "margin-left": {
            "value": "{space-xx-sm}",
            "type": "spacing"
          }
        }
      },
      "shadow-color": {
        "value": "rgba({colors.black-500}, 0.2)",
        "type": "color"
      }
    },
    "loader": {
      "line-1": {
        "value": "{colors.system.primary}",
        "type": "color"
      },
      "line-2": {
        "value": "rgba({colors.system.primary}, 0.7)",
        "type": "color"
      },
      "line-3": {
        "value": "rgba({colors.system.primary}, 0.3)",
        "type": "color"
      }
    },
    "button-icon": {
      "large": {
        "iconfont-typo": {
          "value": {
            "fontFamily": "{icon.font-family}",
            "fontWeight": "{font.weight-light}",
            "lineHeight": "AUTO",
            "fontSize": "{icon.font-size.large}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "none"
          },
          "type": "typography"
        }
      },
      "medium": {
        "iconfont-typo": {
          "value": {
            "fontFamily": "{icon.font-family}",
            "fontWeight": "{font.weight-light}",
            "lineHeight": "AUTO",
            "fontSize": "{icon.font-size.medium}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "none"
          },
          "type": "typography"
        }
      },
      "small": {
        "iconfont-typo": {
          "value": {
            "fontFamily": "{icon.font-family}",
            "fontWeight": "{font.weight-light}",
            "lineHeight": "AUTO",
            "fontSize": "{icon.font-size.small}",
            "letterSpacing": "0%",
            "paragraphSpacing": "0",
            "textDecoration": "none",
            "textCase": "none"
          },
          "type": "typography"
        }
      },
      "border-color-focus": {
        "value": "{button.border-color-focus}",
        "type": "color"
      },
      "on-surface": {
        "icon-color": {
          "value": "{colors.system.secondary}",
          "type": "color"
        },
        "icon-color-hovered": {
          "value": "rgba({colors.system.secondary}, 0.7)",
          "type": "color"
        },
        "icon-color-disabled": {
          "value": "rgba({colors.system.secondary}, 0.3)",
          "type": "color"
        },
        "color-pressed": {
          "value": "rgba({colors.system.secondary}, 0.3)",
          "type": "color"
        }
      },
      "on-secondary": {
        "icon-color": {
          "value": "colors.system.on-secondary",
          "type": "color"
        },
        "icon-color-hovered": {
          "value": "rgba({colors.system.on-secondary}, 0.7)",
          "type": "color"
        },
        "icon-color-disabled": {
          "value": "rgba({colors.system.on-secondary}, 0.3)",
          "type": "color"
        },
        "color-pressed": {
          "value": "rgba({colors.system.on-secondary}, 0.3)",
          "type": "color"
        }
      },
      "on-tertiary": {
        "icon-color": {
          "value": "colors.system.on-tertiary",
          "type": "color"
        },
        "icon-color-hovered": {
          "value": "rgba({colors.system.on-tertiary}, 0.7)",
          "type": "color"
        },
        "icon-color-disabled": {
          "value": "rgba({colors.system.on-tertiary}, 0.3)",
          "type": "color"
        },
        "color-pressed": {
          "value": "rgba({colors.system.on-tertiary}, 0.3)",
          "type": "color"
        }
      }
    },
    "icon": {
      "font-family": {
        "value": "Font Awesome 6 Pro",
        "type": "fontFamilies"
      },
      "font-size": {
        "x-small": {
          "value": "14",
          "type": "fontSizes"
        },
        "small": {
          "value": "16",
          "type": "fontSizes"
        },
        "medium": {
          "value": "{font.size-x-lg}",
          "type": "fontSizes"
        },
        "large": {
          "value": "{font.size-xx-lg}",
          "type": "fontSizes"
        }
      }
    },
    "test-GAP": {
      "value": "{space-sm}",
      "type": "spacing"
    },
    "test-MARGIN": {
      "value": "{space-sm}",
      "type": "spacing"
    },
    "table-item": {
      "background-color-hovered": {
        "value": "{colors.black-020}",
        "type": "color"
      }
    }
  },
  "$themes": [],
  "$metadata": {
    "tokenSetOrder": [
      "global"
    ]
  }
}
```
