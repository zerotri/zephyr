
zephyr_sources_ifdef(CONFIG_GROVE_LCD_RGB grove_lcd_rgb.c)
zephyr_sources_ifdef(CONFIG_MICROBIT_DISPLAY
	mb_display.c
	mb_font.c
)
zephyr_sources_ifdef(CONFIG_ILI9340 display_ili9340.c)
zephyr_sources_ifdef(CONFIG_ILI9340_LCD_ADAFRUIT_1480
	display_ili9340_adafruit_1480.c
)
zephyr_sources_ifdef(CONFIG_SSD1306 ssd1306.c)
zephyr_sources_ifdef(CONFIG_SSD1673 ssd1673.c)

zephyr_sources_ifdef(CONFIG_SDL_DISPLAY display_sdl.c)

zephyr_sources_ifdef(CONFIG_DUMMY_DISPLAY display_dummy.c)

