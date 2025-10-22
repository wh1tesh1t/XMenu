# XMenu

**XMenu** is a **touch client menu** system that uses **script mechanics for Xash3D FWGS** to create menus based on the `numerical_menu` feature.

## Installation

1. **Download** the archive.  
2. **Extract** its contents into your game directory (for example: `cstrike/`, `valve/`, etc.).  
3. **Launch** Xash3D FWGS — the latest version is recommended for stable operation.

---

## Testing the Menu

You can open example menus using the following commands in the console:

```
example_menu1
example_menu2
```

---

## CVAR List

```cfg
set _xmenu_t_build "4.26 2376.01v git"    // Builder Version
set _xmenu_menu_rp "wh1tesh1t"            // Default root path directory
set _xmenu_menu_brp "builder"             // Default root builder path directory
set _xmenu_def_format "cfgpp"             // Default file format

set _xmenu_text_color "240 140 0 255"     // Menu color in <R G B A> format
                                           // WARNING: If CVAR *_AR_COLOR is 1, 
                                           // the menu uses colors from this CVAR.
                                           // Set *_AR_COLORS to 0 to use custom colors.

set _xmenu_ref_color "0 0 0 100"          // Refresh color after next run
                                           // Default: 180 180 180 180 / 0 0 0 180
set _xmenu_text_size "0.90"               // Menu text size (default 1 / max 1.5)
set _xmenu_menu_alp "78"                  // Menu alpha (default 78)

set _xmenu_charset_fix "0"                // Charset fix for UTF-8 text (default 0/1)

set _xmenu_fade "1"                       // Enable fade animation (default 1/0)
set _xmenu_fade_time "4.5 1 0"            // Fade animation timing (default 5 1 0)

set _xmenu_ar_buttons "1"                 // Auto-reset buttons after next builder run (default 1/0)
set _xmenu_ar_colors "1"                  // Auto-reset text/function colors (default 1/2/0)

set _xmenu_stroke_enable "1"              // Enable touch stroke (default 1/0)
set _xmenu_stroke_size "1"                // Touch stroke size (default 1)
set _xmenu_stroke_color "240 140 0 255"   // Touch stroke color (default 255 200 0 255)

set _xmenu_ref_show_fix "1"               // Touch refresh show fix (for old engine)
set _xmenu_ref_key "slot10"
set _xmenu_debug "1"
```

*Taken from configuration file*

---

## ⚠️ Important

This project is **open source**.  
The author **takes no responsibility** for any issues and **recommends downloading only from the official repository**.  
Please **credit the author** to support and help the project grow.
