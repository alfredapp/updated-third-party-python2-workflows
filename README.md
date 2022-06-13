# Updated Third-Party Python 2 Workflows

With macOS Monterey 12.3, Apple [removed the bundled Python 2 interpreter](https://developer.apple.com/documentation/macos-release-notes/macos-12_3-release-notes#Python). That means older Workflows dependent on Python 2 will no longer work without modification.

That’s what this repository is for. It contains existing third-party Python 2 Workflows tweaked so you can keep using them until they are updated by their developers or you switch to an alternative. If a Workflow you use isn’t present, request it [here](https://github.com/alfredapp/updated-third-party-python2-workflows/issues/new?template=request_workflow.yml) or [on the forum](https://www.alfredforum.com/topic/17941-making-python-2-workflows-work-on-macos-monterey-123-and-above/).

Before installing any of these, you **must** follow [the knowledge base article](https://www.alfredapp.com/help/kb/python-2-monterey/) to install Python 2 to a location recognised by Alfred.

**WARNING:** All Workflows in this repository are made by third-parties. They were modified just enough to keep working but *their contents have not been audited* so make sure you trust the original author.

All Workflows retain their original license.

### Workflows

<!-- BEGIN WORKFLOWS TABLE -->
| Name | Updated Version | Original | Alternatives[^1] |
| --- | :---: | :---: | --- |
| AppScripts | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/AppScripts.alfredworkflow) | [View](https://www.alfredforum.com/topic/4218-appscripts-—-list-search-and-run-applescripts-for-the-active-application/) | |
| Ariafred | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Ariafred.alfredworkflow) | [View](https://github.com/Wildog/Ariafred) | |
| Bear | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Bear.alfredworkflow) | [View](https://www.alfredforum.com/topic/10403-bear-workflow-search-and-create-notes/) | |
| Bluetooth Controller | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Bluetooth%20Controller.alfredworkflow) | [View](https://www.alfredforum.com/topic/14589-bluetooth-controller/) | [DenteAzul](https://www.alfredforum.com/topic/10075-denteazul-—-toggle-bluetooth-and-paired-device-connectivity/) |
| Books | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Books.alfredworkflow) | [View](https://www.alfredforum.com/topic/13147-alfred-books-use-alfred-as-an-interface-to-access-apples-books-application/) | |
| Browser Choice | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Browser%20Choice.alfredworkflow) | [View](https://www.alfredforum.com/topic/11787-any-way-to-open-a-url-with-a-particular-browser/) | |
| Calibre Search | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Calibre%20Search.alfredworkflow) | [View](https://github.com/mpco/AlfredWorkflow-Calibre-Search) | |
| Cardhop | Not needed[^3] | [View](https://www.alfredforum.com/topic/10917-cardhop-workflow/) | |
| Cheat | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Cheat.alfredworkflow) | [View](https://www.alfredforum.com/topic/13206-alfred-cheat-manage-your-own-cheat-sheets) | |
| CnyTransform | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/CnyTransform.alfredworkflow) | [View](https://github.com/TerryX-Lee/AlfredWorkflow_CnyTransform) | |
| Confluence Quick Search | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Confluence%20Quick%20Search.alfredworkflow) | [View](https://www.alfredforum.com/topic/10234-atlassian-confluence-quick-search/) | |
| Convert | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Convert.alfredworkflow) | [View](https://www.alfredforum.com/topic/3980-offline-unit-conversion-workflow/) | [Convert](https://github.com/giovannicoppola/alfred-convert) 𐄁 [Calculate Anything](https://github.com/biati-digital/alfred-calculate-anything) |
| Date Calculator | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Date%20Calculator.alfredworkflow) | [View](https://github.com/MuppetGate/Alfred-Workflows-DateCalculator) | |
| Default Folder X | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Default%20Folder%20X.alfredworkflow) | [View](https://www.alfredforum.com/topic/8695-default-folder-x/) | |
| Dict.cc | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Dict.cc.alfredworkflow) | [View](https://github.com/dennis-tra/alfred-dict.cc-workflow) | [Dict.cc](https://github.com/dennis-tra/alfred-dict.cc-workflow) |
| ESV Online Bible | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/ESV%20Online%20Bible.alfredworkflow) | [View](https://www.alfredforum.com/topic/9663-esv-online-bible/) | |
| Ekşi Sözlük | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Ekşi%20Sözlük.alfredworkflow) | [View](https://github.com/ttuygun/alfred-eksi-sozluk-workflow) | |
| Epoch Converter | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Epoch%20Converter.alfredworkflow) | [View](https://www.alfredforum.com/topic/12048-epoch-converter/) | [Epoch Converter](https://github.com/giovannicoppola/alfred-epoch-converter) |
| Fakeum | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Fakeum.alfredworkflow) | [View](https://www.alfredforum.com/topic/5319-fakeum-—-generate-fake-test-datasets-in-alfred/) | [Fakeum](https://github.com/giovannicoppola/alfred-fakeum) |
| Favorites | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Favorites.alfredworkflow) | [View](http://www.packal.org/workflow/favorites) | |
| File Renamer | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/File%20Renamer.alfredworkflow) | [View](https://github.com/realliyifei/alfred-file-renamer) | [RenameAction](https://www.alfredforum.com/topic/2722-renameaction-—-rename-files-and-folders/) |
| Git Repos | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Git%20Repos.alfredworkflow) | [View](https://www.alfredforum.com/topic/4588-find-filter-open-git-repositories/) | |
| Google Authenticator | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Google%20Authenticator.alfredworkflow) | [View](https://www.alfredforum.com/topic/4062-gauth-google-authenticator-time-based-two-factor-authentication/) | [Google Authenticator](https://github.com/tbrek/alfred-workflow-gauth/)
| Google Chrome History | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Google%20Chrome%20History.alfredworkflow) | [View](https://github.com/tupton/alfred-chrome-history) | [Chromium History and Bookmark Search](https://www.alfredforum.com/topic/13788-chromium-bookmarks-and-history-search/) |
| Homebrew and Cask | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Homebrew%20and%20Cask.alfredworkflow) | [View](https://www.alfredforum.com/topic/4270-homebrew-and-cask-for-alfred/) | |
| I Sheet You Not | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/I%20Sheet%20You%20Not.alfredworkflow) | [View](https://www.alfredforum.com/topic/9469-i-sheet-you-not-plug-excel-into-alfred/) | |
| Jira Search | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Jira%20Search.alfredworkflow) | [View](https://www.packal.org/workflow/jira-search) | [Jira](https://github.com/mjhuber/alfred-jira) 𐄁 [Jira Server Utilities](https://github.com/scarstens/alfred-workflow-jira-search-utilities) 𐄁 [Jira Search](https://github.com/titouanmathis/alfred-jira-search) |
| JustWatch | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/JustWatch.alfredworkflow) | [View](https://www.alfredforum.com/topic/14853-justwatch-alfred-workflow/) | [JustWatch](https://github.com/vinaywadhwa/justwatch-alfred) |
| Microsoft ToDo | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Microsoft%20ToDo.alfredworkflow) | [View](https://www.alfredforum.com/topic/14864-microsoft-todo-wunderlist-replacement-workflow/) | |
| NSC | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/NSC.alfredworkflow) | [View](https://www.alfredforum.com/topic/1975-nsc-number-system-converter/) | |
| Network Location | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Network%20Location.alfredworkflow) | [View](https://www.alfredforum.com/topic/4533-list-filter-and-activate-network-locations-from-within-alfred/) | |
| OneNote Navigator | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/OneNote%20Navigator.alfredworkflow) | [View](https://github.com/kevin-funderburg/alfred-microsoft-onenote-navigator) | |
| Open iTerm Profile | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Open%20iTerm%20Profile.alfredworkflow) | [View](https://github.com/jessedobbelaere/alfred-iterm-profiles-workflow) | |
| Outlook Search | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Outlook%20Search.alfredworkflow) | [View](https://www.alfredforum.com/topic/11320-workflow-for-outlook-v16-search/) | |
| Password Generator[^2] | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Password%20Generator.alfredworkflow) | [View](https://www.alfredforum.com/topic/6653-secure-password-generator/) | [StrongPassword](https://www.alfredforum.com/topic/1233-strongpassword) |
| Paste N Clipboards | Not needed[^3] | [View](https://www.packal.org/workflow/paste-n-clipboards) | [SequentialPaste](https://www.alfredforum.com/topic/14534-sequentialpaste-—-paste-previous-clipboard-entries-in-order/) |
| Percent Change | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Percent%20Change.alfredworkflow) | [View](https://www.alfredforum.com/topic/4731-percent-change/) | [Percent Change](https://github.com/giovannicoppola/alfred-percent-change) |
| Philips Hue Controller | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Philips%20Hue%20Controller.alfredworkflow) | [View](https://www.alfredforum.com/topic/2723-philips-hue-controller-workflow/) | |
| Pocket | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Pocket.alfredworkflow) | [View](https://www.alfredforum.com/topic/4127-pocket-for-alfred/) | |
| Power Thesaurus | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Power%20Thesaurus.alfredworkflow) | [View](https://www.alfredforum.com/topic/10576-power-thesaurus-search/) | [Power Thesaurus](https://github.com/giovannicoppola/alfred-powerthesaurus) 𐄁 [SynAnt](https://www.alfredforum.com/topic/3954-synant) |
| Pyocr | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Pyocr.alfredworkflow) | [View](https://github.com/AcerFeng/Pyocr-Alfredworkflow) | |
| Reddit | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Reddit.alfredworkflow) | [View](https://www.alfredforum.com/topic/5317-browse-reddit/) | |
| Relative Dates | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Relative%20Dates.alfredworkflow) | [View](https://www.alfredforum.com/topic/4056-relative-dates/) | |
| Safari History | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Safari%20History.alfredworkflow) | [View](https://github.com/tupton/alfred-safari-history) | [Safari Toolkit](https://github.com/addozhang/alfred-safari-toolkit) |
| Salesforce | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Salesforce.alfredworkflow) | [View](https://www.alfredforum.com/topic/10892-search-in-salesforce-alfred-3-worklfow/) | |
| Seq-utilities | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Seq-utilities.alfredworkflow) | [View](https://github.com/danielecook/seq-utilities-alfred) | |
| Shell Variables | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Shell%20Variables.alfredworkflow) | [View](https://github.com/hug33k/Alfred-ShellVariables) | |
| Skimmer | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Skimmer.alfredworkflow) | [View](https://www.alfredforum.com/topic/4052-skimmer-pdf-actions-for-skim/) | [PDF Tools](https://www.alfredforum.com/topic/9276-alfred-pdf-tools-–-optimize-encrypt-and-manipulate-pdf-files/) |
| Smart Folders | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Smart%20Folders.alfredworkflow) | [View](https://www.alfredforum.com/topic/3385-smartfolders-browse-and-search-the-contents-of-your-saved-searches/) | |
| SmartThings | Not needed[^3] | [View](https://github.com/mattnichols/SmartThings-Alfred) | |
| SpeedTest | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/SpeedTest.alfredworkflow) | [View](http://www.packal.org/workflow/speedtest-0) | [Network Quality](https://www.alfredforum.com/topic/18257-network-quality-—-test-your-internet-connection/) |
| StackExchange Search | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/StackExchange%20Search.alfredworkflow) | [View](https://www.alfredforum.com/topic/5318-search-stackoverflow/) | |
| Star Ratings | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Star%20Ratings.alfredworkflow) | [View](https://www.alfredforum.com/topic/8132-star-ratings-rate-your-files-like-in-itunes/) | |
| TeXdoc | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/TeXdoc.alfredworkflow) | [View](https://www.alfredforum.com/topic/8705-texdoc-workflow/) | |
| Timing | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Timing.alfredworkflow) | [View](https://github.com/zhengyu-yang/alfred-timing) | |
| Unicode Symbols Search | Not needed[^3] | [View](https://www.alfredforum.com/topic/1404-find-and-paste-unicode-symbols-arrow-triangles-greek-and-more/) | [Unicode](https://github.com/deanishe/alfred-unicode) |
| VPN Manager | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/VPN%20Manager.alfredworkflow) | [View](https://www.alfredforum.com/topic/7333-vpn-connection-manager/) | |
| Video Conferences | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Video%20Conferences.alfredworkflow) | [View](https://www.deanishe.net/post/2020/05/workflow-video-conferences/) | |
| Wi-Fi Control | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Wi-Fi%20Control.alfredworkflow) | [View](https://github.com/miromannino/alfred-wifi-control) | |
| Word Search | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/Word%20Search.alfredworkflow) | [View](https://www.alfredforum.com/topic/11074-word-search-a-workflow-to-make-you-a-better-writer/) | [Word Search](https://github.com/jun6lee/Alfred-WordSearch) 𐄁 [Power Thesaurus](https://github.com/giovannicoppola/alfred-powerthesaurus) 𐄁 [SynAnt](https://www.alfredforum.com/topic/3954-synant) |
| ZotHero[^2] | [Download](https://github.com/alfredapp/updated-third-party-python2-workflows/raw/main/Workflows/ZotHero.alfredworkflow) | [View](https://www.alfredforum.com/topic/11658-zothero-—-generate-zotero-citations-in-alfred/) | |
<!-- END WORKFLOWS TABLE -->

### Officially updated

Workflows which used to be on the table above but have since been updated by their developers.

| Name | Web Page |
| --- | :---: |
| Calendar | [View](https://github.com/cleobis/alfred-cal) |
| Case Converter| [View](https://www.alfredforum.com/topic/2180-case-converter-including-title-case/) |
| Change Case | [View](https://github.com/gillibrand/alfred-change-case) |
| Emoji Taco | [View](http://github.com/jeeftor/EmojiTaco) |
| Movie and TV Show Search | [View](https://www.alfredforum.com/topic/5355-movie-and-tv-show-search/) |
| PDF Tools | [View](https://www.alfredforum.com/topic/9276-alfred-pdf-tools-–-optimize-encrypt-and-manipulate-pdf-files/) |
| Search OmniFocus | [View](https://github.com/rhydlewis/alfred-search-omnifocus) |
| Session | [View](https://www.alfredforum.com/topic/17627-session-workflow/) |
| Tailwind CSS Docs | [View](https://github.com/techouse/alfred-tailwindcss-docs) |
| The Archive | [View](https://www.alfredforum.com/topic/15090-alfred-workflow-for-the-archive/) |

[^1]: Alternatives don’t depend on Python 2 but may have a different set of features. [Use the template](https://github.com/alfredapp/updated-third-party-python2-workflows/issues/new?template=suggest_alternative.yml) to suggest an alternative.

[^2]: This Workflow depends on the Objective-C bridge for some of its functionality. Install it with `"${HOME}/.pyenv/versions/2.7.18/bin/python2.7" -m pip install PyObjC`. It may fail to build on Apple Silicon.

[^3]: Despite having been requested, this Workflow doesn’t need modifications to work. Following the [instructions to reinstall Python 2](https://www.alfredapp.com/help/kb/python-2-monterey/) is enough.
