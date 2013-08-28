##Version 2.0

* Location sync with Marvin for iPad, iPhone and iPod touch.
* Compatibility improvements with future iOS versions.
* Refreshed UI and icon.
* Edge-to-edge screen scrolling.
* Faster page rendering.
* Improved battery life.
* Library organizer, sub-organizer, and book search panels can be swiped to close.
* Animated slide indicators for rows.
* Support for GIF covers.
* Reading menu (“Aa” menu) opens much faster.
* In the formatting tab of the reading menu (“Aa” menu), “text size” is now a switch to and from "Normal" and "Uniform" font sizing options. This is useful for books that have combinations of very small and very large text and a comfortable text size cannot be found.
* Improved how Marvin displays text sizes in a book.
* In-book toolbars are automatically hidden when selecting a chapter, section, highlight or bookmark from the ToC screen.
* Tap zone of the book title header and “tap to go back” is larger and easier to hit.
* 2 new ePaper colours in book themes.
* Lists in theme color and font picker automatically scroll to show the current selection.
* User-selectable page number formatting. Setting in device’s Settings.app.
* Screensaver in calibre connection mode.
* Performance and cosmetic upgrades to calibre connector.
* Added a progress bar-only option to “Page titles and footers” option in general settings (gear icon).
* Added spinning load animation between chapters. This is less intrusive than the big “Opening chapter…” alert.
* Minor text and layout changes in exported HTML files.
* Fixed: Some covers weren’t centered properly.
* Fixed: Some books showed without a ToC.
* Fixed: When viewing a book in publisher’s formatting and in portrait orientation, rotating to landscape and then back to portrait causes the current page to shift downwards.
* Fixed: Network activity spinner was not showing during OPDS activity.
* Fixed typo “IMDB” -> “IMDb”.

##Version 1.8 (2013-07-27)

* Improved compatibility with iOS 7 beta.
* Marvin starts up about 2.5x faster (especially noticeable if you have many books).
* Chapter loading is about 15% 25% faster.
* Improved layout engine and other iOS 5-specific enhancements.
* Improved EPUB compatibility.
* Fixed searching in COPS.
* Fixed an in-book toolbar alignment problem when rotating the device.
* Corrected some typos and some other minor fixes.

##Version 1.71 (2013-07-02)

* OPDS parsing improvements.
* Improved compatibility with damaged EPUBs having missing containers. 
* Updated preset for Abbyy Lingvo URL scheme.
* Fixed: library screen could hang when trying to open a damaged book.


##Version 1.7 (2013-06-20)

* Native calibre device driver (developed with Greg Riker)
* New overlapping toolbar design (in preparation for iPhone).
* In-book toolbar auto hides after entering a book.
* In-book toolbar buttons and slider have more contrast.
* Substantial layout improvements and fidelity.
* Per book publisher’s settings switch and embedded fonts.
* Chapter loading is up to 30% faster.
* Variable vertical margins. Set up in “General” settings (small/medium/large).
* Chapter-to-chapter transitions are less choppy (especially for converted comics and chapters whose first/last pages contain images).
* Layout tab of in-book menu item has been reorganized in "Format" and "Page" tabs.
* The "more details" ellipses button in an OPDS entry is available even for non-EPUB books.
* {title} and {author} placeholders in custom menu commands and URL schemes.
* New squashed bookmark design to avoid overlaps on text (tappable area is actually much larger even though the bookmark may look smaller).
* Top-right corner of book is a "hot zone" to add bookmarks.
* Surface area of slider thumbnail is larger (to grab it more easily).
* Lock orientation setting moved from home screen “General” tab to the in-book “Page” tab.
* Reorganized some options in the “General” settings tab.
* Replaced bulk edit pencil icon in library with a checkmark icon (was causing confusion with the pencil icon in organizer).
* Global setting to “Hide status bar while reading” is now automatic. The status bar is always visible when the toolbar is visible and always hidden when the toolbar is hidden.
* Option to show clock in full screen (status bar hidden mode).
* Fixed: Marvin wouldn’t see covers of books imported after the calibre "polish books" plugin has been applied.

##Version 1.6 (2013-05-31)

* Extend selection by a sentence now works iteratively. Extending multiple times will make the current selection grow by a sentence each time.
* If a selection is extended into the next page, Marvin will automatically scroll to that page.
* Added a new setting in Settings.app (iPad settings) to use a smaller, sans-serif font for notes.
* Improved compatibility with some malformed books.
* Updated tutorial text to include Chinese and Japanese to the explanation of how offline iOS dictionaries work.
* Fixed a UI alignment issue in the web browser toolbar.
* Updated some UI elements.

##Version 1.55 (2013-05-18)

* Marvin imports books up to 8x faster.
* Library scrolling tips help you locate books in long lists much faster.
* Improved compatibility with O’Reilly DRM free books.
* Fixed: An OPDS search in the Internet Archive was returning incomplete results.
* Improved compatibility of exported HTML files with word processors.
* Added a tutorial page and tip to explain how the offline system dictionary works.
* Miscellaneous bug fixes.

##Version 1.5 (2013-05-04)

* You can create custom in-book menu commands (e.g. translate, Wikipedia, Wiktionary, launch apps, copy text, etc…). Go to “Home > Settings > Menu” to set them up.
* Presets for Wikipedia, Wiktionary, Google Translate, Merriam-Webster online dictionary, Bing image search, Google Maps, Goodreads quote search, Twitter, Facebook, ABBYY Lingvo, Tweetbot, Google Chrome, Rambler, Duden, Nebulous, IMDB and many other commands.
* Of course, you can create your own commands.
* Standard in-book menus use icons.
* Removed experimental iOS dictionary support.
* Added Wiktionary online dictionaries for en, de, es, fr, hi, it, ja, kr, nl, pl, ru, and zh.
* You can create a command to any custom online dictionary you like.
* Finer line spacing increments.
* Share > Web opens in Marvin’s built-in web browser instead of Safari.
* Improved OPDS searching. Marvin can now search in several new catalogs such as COPS, Project Gutenberg, Internet Archive and Feedbooks.
* Marvin remembers the “last formatting” used globally. The default formatting applied to a newly opened book doesn’t depend on a previously opened book existing.
* The Deep View and in-book web browser allows you to pin web pages even if they’re still loading.
* Improved font resizing compatibility (buttons “A+” and “A-” in web browser)
* Option to turn off cover animation in home screen (setting is in iPad’s settings not Marvin’s settings).
* New monospaced font - "Liberation Mono".
* Updated some text in the OPDS favorite box to make the process clearer.
* Updated some “about” text.
* Added “Custom menu commands” section to tutorial.
* Some other bug fixes.

##Version 1.46 (2013-04-19)

* Fixed a bug that sometimes causes Marvin to crash when deleting a custom collection.
* Fixed a bug that could cause duplicates of the same word being added to the vocabulary.
* Fixed a problem where highlighted text displays incorrectly for some font sizes.
* Added a confirmation message before deleting a word from the vocabulary of a book.
* The library view is re-sorted automatically when you change the metadata for a book.
* Fixed some other small issues.

##Version 1.45 (2013-04-12)

* You can share reading status, progress, selected text, highlights, notes and even pictures on Twitter and Facebook (Facebook sharing requires iOS 6 or better).
* Library has been redesigned from the ground up with faster loading and advanced management.
* Reading list, custom and smart collections.
* Bulk editing in library.
* Full-book searching.
* Search results can be sent by email for reference.
* Improved OPDS and Web browser with improved download performance.
* Queued OPDS downloads.
* Faster start up times.
* New global vocabulary (access from the Library Organizer).
* Words in your vocabulary are not deleted if the associated book is deleted from your library.
* New extra-dimming option in book brightness controls for more comfortable night-time reading.
* Indicators next to flagged books, read books and books in your reading list.
* Hidden/locked books are faded out and do not show on your home screen.
* After a database update, Marvin will perform optimization tasks for better performance.
* Marvin remembers the last highlight color you used.
* Reduced the likelihood that highlighted text has its descenders cut off.
* Highlights and notes can be exported to CSV files. This is great for proof readers and index creators.
* Emails with attachments are generated more smoothly.
* Improved response time of Deep View screen having many names.
* FIX: MRVI files exported to the documents directory where not overwriting old ones.
* Other bug fixes, performance improvements and polishing.

##Version 1.3 (2013-03-11)

* Make Marvin your own! Choose from 8 cool themes (requires an In-App Purchase).
* In-App Purchases can be password-protected (Home Screen, Settings, More).
* Marvin plays well with others. The OPDS browser lets you download pdf, mobi, cbr, pdb, rtf and many other eBook file types and Marvin will open them in another app.
* Marvin starts up 5x to 10x faster (from the second startup onwards, adding new books takes the same time to import).
* "My Dictionary" is now called "Vocabulary".
* You can export your vocabulary and keep it for reference or share it. You can also send the vocabulary in all the books in your library at once.
* Vocabularies can be exported as CSV files (Microsoft Excel for Mac has problems importing some Unicode characters properly).
* Deeper integration and annotation syncing with Calibre (Home Screen, Settings, Services, Calibre).
* Reminder popup now shows current reading time.
* Added custom reminders.
* Added reminder setup message.
* You can search the internet for cover images straight from within the metadata editor.
* Password-protected books show a ‘locked’ indicator.
* Added fade animation back (Home Screen, Settings, Page Turn Style).
* Marvin remembers the last page and position you were in the Book Content view (ToC/Bookmarks/Highlights/Vocabulary).
* Words added to your vocabulary are no longer automatically capitalized.
* Added “Delete All” functionality in vocabulary.
* The annotations file (\*.mrv) now includes words added to your vocabulary and they can be imported back.
* Improved download of book descriptions in OPDS browser (better compatibility with calibre2opds).
* Book subjects/tags are exported in annotations file.
* Fixed: Importing a Marvin annotations file (*.mrv) could cause Marvin to hang if the file is damaged.
* XHTML files are exported with an HTML extension to work better with iOS 6.
* Calibre series number now only accepts numeric values in the metadata editor.
* Fixed sorting of calibre series number in library.
* Changed the way calibre series numbers are displayed
* Reminder time is shown as specified by device’s region settings (12/24 hr).
* Fixed an occasional crash when performing Deep View analysis on a non-English book.
* Fixed a random crash when downloading books by OPDS or Web Browser.
* Improvements in how Marvin displays dates.
* Added help screen to metadata editor.
* A single tap on an image was ignored. Now it isn’t.
* Squashed a bug that prevented your iPad from going to sleep when Marvin is running.
* Corrected the behavior of multi-file downloads in Dropbox.
* Other bug fixes and polishing.

##Version 1.25 (2013-02-12)

* Marvin remembers any words you look up in the dictionary and helps you build a vocabulary. To access your word list, go to the Table of Contents screen in your book.
* Added password protection to limit access to certain books in your library (activate in “More” tab in settings).
* Added external link indicators next to buttons that take you out of Marvin.
* Improved behavior of library sort by Calibre series and index.
* Changed caching behavior in OPDS browser.
* "Cloud" tab in settings is renamed to "Services".
* Added a button to add a new OPDS catalog in the favourites popup.
* When the library is opened, the search box is shown with an animation.
* Renamed “OPDS” to “OPDS Catalogs” in cloud popup.
* Added a slight border around the cover of the current book in the home screen.
* Fixed a bug that could cause Marvin to crash on startup.
* Fixed a typo in Add Web Favorite dialog.
* Fixed some tutorial text.

##Version 1.2 (2013-02-02)

* Two-column reading.
* Smoother page turn animations (no more flicker in dark themes).
* Variable page turn animation speed.
* Paragraph spacing respects the original layout in the book.
* Page is a bit higher and fits an extra line of text (for some font sizes).
* Substantial speed improvements especially in chapters contain lots of links and improved battery life.
* Changing brightness/warmth/tint from the menu shows the percentage in the heads up display.
* Improved rendering of font sizes.
* The time read message shown when leaving a book compensates for the time the device is sleeping or off.
* German, Spanish and French dictionaries (requires iOS 6). Dictionaries may not be available if they haven’t been downloaded.
* Paragraph spacing in page layout controls.
* 2 lovely, highly-readable fonts: Charis SIL and Open Sans.
* Tap gesture to quickly cycle through themes without going into the menu.
* "Mini progress bar" at the bottom of the page.
* Book info (tapping the title of the page) shows the book cover and description.
* Customizable three-finger swipe gesture.
* Added 45 minute interval for book reminder.
* Added custom reminder message in timer.
* Highlights with a note have a subtle underline.
* A new, purple highlight style.
* Notes are shown in highlight list.
* Marvin no longer indents paragraphs that shouldn’t be indented.
* Tap for last position remembers multiple last positions.
* Tap for last position also works for link navigation in the same chapter.
* Added mini progress bar at the bottom of the “now reading” section of the home screen.
* Finer paragraph indent increments.
* Marvin no longer mistakes horizontal page turn swipes for brightness/warmth vertical swipes (even if you horizontally swipe from the middle).
* Built in OPDS Browser with support for search and authentication over HTTP and HTTPS.
* Built in Web Browser designed to browse eBook websites and Calibre server.
* Added selective Dropbox search folder in settings.
* You can compute word counts on a per-book basis.
* Library search by series and subjects.
* See author sort, Calibre series, Calibre series index (number) and subjects (tags) in library expanded view.
* Library can be sorted by author sort, and Calibre series and index (number).
* Metadata editor with support for changing cover images.
* Marvin parses author sort, title sort, description, Calibre series, Calibre series number and UUID from books.
* Author sort field jump list in library.
* Calibre series jump list in library.
* First letter picker for book title, author, author sort and calibre series.
* Progress is displayed as a pie chart in library condensed mode.
* Export bookmarks, highlights and annotations to a format that can be restored later or shared with friends for import into their books.
* Book titles in library are normalized for easier sorting and selection (“The Lord of the Rings” = “Lord of the Rings, The”).
* Changed style of book progress bar in library.
* New, cooler, library shuffle animation.
* Landscape orientation lock setting.
* Setting to launch Marvin into the last opened book.
* Don’t launch to book iPad system preference (part of diagnostics).
* Added slower page turn animation speed (now there are 4 settings: Off, Fast, Medium, Slow).
* Added page title and footer brightness control (now there are 3 settings: Hidden, Dim, Bright).
* Moved multi-colour bookmarks to “More” settings.
* Renamed “Back” buttons to the page they are going back to (e.g. “Library”).
* Reordered back button with the web back button used for navigation.
* Some cover images were not centered.
* Corrected Facebook link to open properly in Marvin’s Facebook page.
* Corrected text of summary book description field.
* Faster and more memory efficient library loading.
* Removed period after timestamp when exporting highlights and notes.
* Updated some colours and UI accents.
* More robust detection of encrypted ePubs.
* Marvin no longer shows the “Opening chapter…” message when opening very short chapters.
* In some cases Marvin offered to install bundled books even if the library is not empty.
* Refresh button in library was not disabled when a menu is shown.
* Pinning articles without a title to Deep View caused Marvin to crash.
* Long book titles now show in Book Info popup (when you tap the header in the book).
* More robust when detecting cover images.
* More robust when opening books with a damaged NCX.
* Paragraph indenting wasn’t working on some books.
* Fixed an problem where rotating your iPad when Marvin is analysing your book causes an error (and in very rare instances, database corruption).
* Renamed the first instance of “Khaki” to “Light Khaki” (the colour name was duplicate).
* Moved back button in web browsers to the top toolbar.
* Improved compatibility with many books.
* Repeatedly and rapidly tapping the bookmarks toolbar button causes the button and the bookmark to become invisible.
* Corrected typos and tutorial text.
* Fixed reset button text on book layout menu to reflect better that fonts, and themes are reset too.
* Small bug fixes and layout improvements.

##Version 1.16 (2012-12-20)

* Fix: New users cannot link to their Dropbox account.

##Version 1.15 (2012-12-14)

* Tapping “Deep View” on a name in the text shows you the first occurrences of that name in the book without leaving the text.
* Dropbox file list now shows a maximum of 1,000 books (the maximum the Dropbox API allows).
* If the official Dropbox app is installed you can open it from within Marvin’s Dropbox screen.
* Deep View can be partially reset. This is useful, if you want to reanalyze the book for names (because of an upgraded, better version of Marvin) but don’t want to lose the articles you pinned.
* Checkmarks next to selected fonts and theme colors.
* Reset settings to default values (themes, fonts, gestures, etc…)
* Title text of a page now alternates between the book name, author name and overall progress in the book.
* New minimalist mode in general settings to hide page titles and footers when reading.
* New setting under timer to show you how long you’ve read just before leaving the book.
* Faster summary generation.
* Added text labels to make it more obvious that font and color lists are scrollable.
* Added ‘marvinapp://’ launch URL scheme.
* Added link to Facebook page in general settings.
* Marvin is more robust when opening slightly malformed ePub books.
* Improved stability when launching in the presence of corrupted books.
* Diagnostic startup mode in iPad settings (do not turn this on unless asked by support).
* Minor bug fixes and polishing.

##Version 1.1 (2012-12-05)

* First occurrence text of a name shows more detail (multiple occurrences).
* Added a send button to the first occurrence popup to share it by email.
* New search box to filter books in your Dropbox.
* Page warmth and tint settings now apply to all in-book menus, table of contents and Deep View.
* Added a global setting to prevent screen dimming and locking when reading.
* Added a setting to detect and prevent accidental page turns when holding your iPad by its sides.
* All send by email functionality extended to work with friends list.
* Added a reload button in built-in web browser.
* Added ‘Little Brother’ by Cory Doctorow as a new book in the stock library.
* Upgraded to the latest version of OpenDyslexic with updated characters and improved spacing.
* File extension is hidden in Dropbox file list.
* Much better accuracy in Deep View name recognition.
* Updated some graphics.
* Fixed: Highlighted text was not visible in some theme color combinations.
* Fixed: On very rare occasions, loading a chapter caused Marvin to hang.
* Fixed: Some highlights created after searching in a chapter could be lost.
* Fixed: Some SVG images were not zoomable.
* Minor bug fixes and polishing.

##Version 1.0 (2012-11-21)

* Initial release
