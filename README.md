# PLUGIN-DRM-CALIBRE-DOESN-T-WORK
I have installed calibre 3.48 version and plugin 6.6.2.
calibre Registro de depuración
calibre 3.48 [64bit]  embedded-python: True is64bit: True
Windows-10-10.0.17134-SP0 Windows ('64bit', 'WindowsPE')
('Windows', '10', '10.0.17134')
Python 2.7.15+
Windows: ('10', '10.0.17134', 'SP0', u'Multiprocessor Free')
Interface language: es
Successfully initialized third party plugins: DeDRM (6, 6, 2)
calibre 3.48 [64bit]  embedded-python: True is64bit: True
Windows-10-10.0.17134-SP0 Windows ('64bit', 'WindowsPE')
('Windows', '10', '10.0.17134')
Python 2.7.15+
Windows: ('10', '10.0.17134', 'SP0', u'Multiprocessor Free')
Interface language: es
Successfully initialized third party plugins: DeDRM (6, 6, 2)
Turning on automatic hidpi scaling
devicePixelRatio: 1.0
logicalDpi: 96.0 x 96.0
physicalDpi: 100.861627907 x 101.07357513
Using calibre Qt style: True
[0.00] Starting up...
[0.00] Showing splash screen...
[0.12] splash screen shown
[0.12] Initializing db...
[0.14] db initialized
[0.14] Constructing main UI...
[1.62] main UI initialized...
[1.62] Hiding splash screen
[9.66] splash screen hidden
[9.66] Started up in 9.66 seconds with 3 books
DeDRM v6.6.2: Trying to decrypt El secreto de la orquÃ­dea.epub
DeDRM v6.6.2: Verifying zip archive integrity
DeDRM v6.6.2: El secreto de la orquÃ­dea.epub is a secure Adobe Adept ePub
DeDRM v6.6.2: Trying Encryption key default_key
Could not decrypt znjw7y.epub. Wrong key
DeDRM v6.6.2: Failed to decrypt with key default_key after 0.1 seconds
DeDRM v6.6.2: Looking for new default Adobe Digital Editions Keys after 0.1 seconds
Found 1 keys
DeDRM v6.6.2: Ultimately failed to decrypt after 0.1 seconds. Read the FAQs at Harper's repository: https://github.com/apprenticeharper/DeDRM_tools/blob/master/FAQs.md
Running file type plugin DeDRM failed with traceback:
Traceback (most recent call last):
  File "site-packages\calibre\customize\ui.py", line 172, in _run_filetype_plugins
  File "calibre_plugins.dedrm.__init__", line 633, in run
  File "calibre_plugins.dedrm.__init__", line 404, in ePubDecrypt
DeDRMError: DeDRM v6.6.2: Ultimately failed to decrypt after 0.1 seconds. Read the FAQs at Harper's repository: https://github.com/apprenticeharper/DeDRM_tools/blob/master/FAQs.md
C:\Program Files\Calibre2\app\pylib.zip\dateutil\parser.py:601: UnicodeWarning: Unicode equal comparison failed to convert both arguments to Unicode - interpreting them as being unequal
Added El secreto de la orquídea to db in: 1.7
Added 1 books in 2.9 seconds
Worker Launch took: 0.446999788284
Job: 0 Convertido el libro 1 de 1 (El secreto de la orquídea) finished
Convertido el libro 1 de 1 (El secreto de la orquídea)
	C:\Program Files\Calibre2\app\pylib.zip\dateutil\parser.py:601: UnicodeWarning: Unicode equal comparison failed to convert both arguments to Unicode - interpreting them as being unequal
	Conversion options changed from defaults:
	  output_profile: u'kindle'
	  read_metadata_from_opf: u'C:\\Users\\asus\\AppData\\Local\\Temp\\calibre_k2ifuz\\csiesu.opf'
	  verbose: 2
	Resolved conversion options
	calibre version: 3.48.0
	{'asciiize': False,
	 'author_sort': None,
	 'authors': None,
	 'base_font_size': 0.0,
	 'book_producer': None,
	 'change_justification': u'original',
	 'chapter': u"//*[((name()='h1' or name()='h2') and re:test(., '\\s*((chapter|book|section|part)\\s+)|((prolog|prologue|epilogue)(\\s+|$))', 'i')) or @class = 'chapter']",
	 'chapter_mark': u'pagebreak',
	 'comments': None,
	 'cover': None,
	 'debug_pipeline': None,
	 'dehyphenate': True,
	 'delete_blank_paragraphs': True,
	 'disable_font_rescaling': False,
	 'dont_compress': False,
	 'duplicate_links_in_toc': False,
	 'embed_all_fonts': False,
	 'embed_font_family': None,
	 'enable_heuristics': False,
	 'expand_css': False,
	 'extra_css': None,
	 'extract_to': None,
	 'filter_css': u'',
	 'fix_indents': True,
	 'font_size_mapping': None,
	 'format_scene_breaks': True,
	 'html_unwrap_factor': 0.4,
	 'input_encoding': None,
	 'input_profile': <calibre.customize.profiles.InputProfile object at 0x0000021737879240>,
	 'insert_blank_line': False,
	 'insert_blank_line_size': 0.5,
	 'insert_metadata': False,
	 'isbn': None,
	 'italicize_common_cases': True,
	 'keep_ligatures': False,
	 'language': None,
	 'level1_toc': None,
	 'level2_toc': None,
	 'level3_toc': None,
	 'line_height': 0.0,
	 'linearize_tables': False,
	 'margin_bottom': 5.0,
	 'margin_left': 5.0,
	 'margin_right': 5.0,
	 'margin_top': 5.0,
	 'markup_chapter_headings': True,
	 'max_toc_links': 50,
	 'minimum_line_height': 120.0,
	 'mobi_file_type': u'old',
	 'mobi_ignore_margins': False,
	 'mobi_keep_original_images': False,
	 'mobi_toc_at_start': False,
	 'no_chapters_in_toc': False,
	 'no_inline_navbars': True,
	 'no_inline_toc': False,
	 'output_profile': <calibre.customize.profiles.KindleOutput object at 0x0000021737879828>,
	 'page_breaks_before': u'/',
	 'personal_doc': u'[PDOC]',
	 'prefer_author_sort': False,
	 'prefer_metadata_cover': False,
	 'pretty_print': False,
	 'pubdate': None,
	 'publisher': None,
	 'rating': None,
	 'read_metadata_from_opf': u'C:\\Users\\asus\\AppData\\Local\\Temp\\calibre_k2ifuz\\csiesu.opf',
	 'remove_fake_margins': True,
	 'remove_first_image': False,
	 'remove_paragraph_spacing': False,
	 'remove_paragraph_spacing_indent_size': 1.5,
	 'renumber_headings': True,
	 'replace_scene_breaks': u'',
	 'search_replace': '[]',
	 'series': None,
	 'series_index': None,
	 'share_not_sync': False,
	 'smarten_punctuation': False,
	 'sr1_replace': None,
	 'sr1_search': None,
	 'sr2_replace': None,
	 'sr2_search': None,
	 'sr3_replace': None,
	 'sr3_search': None,
	 'start_reading_at': None,
	 'subset_embedded_fonts': False,
	 'tags': None,
	 'timestamp': None,
	 'title': None,
	 'title_sort': None,
	 'toc_filter': None,
	 'toc_threshold': 6,
	 'toc_title': None,
	 'transform_css_rules': '[]',
	 'unsmarten_punctuation': False,
	 'unwrap_lines': True,
	 'use_auto_toc': False,
	 'verbose': 2}
	InputFormatPlugin: EPUB Input running
	on C:\Users\asus\AppData\Local\Temp\calibre_k2ifuz\s71z2o.epub
	Python function terminated unexpectedly
	  s71z2o.epub (Error Code: 1)
	Traceback (most recent call last):
	  File "site.py", line 101, in main
	  File "site.py", line 78, in run_entry_point
	  File "site-packages\calibre\utils\ipc\worker.py", line 199, in main
	  File "site-packages\calibre\gui2\convert\gui_conversion.py", line 43, in gui_convert_override
	  File "site-packages\calibre\gui2\convert\gui_conversion.py", line 28, in gui_convert
	  File "site-packages\calibre\ebooks\conversion\plumber.py", line 1110, in run
	  File "site-packages\calibre\customize\conversion.py", line 246, in __call__
	  File "site-packages\calibre\ebooks\conversion\plugins\epub_input.py", line 290, in convert
	calibre.ebooks.DRMError: s71z2o.epub

