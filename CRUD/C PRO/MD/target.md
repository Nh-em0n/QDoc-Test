ftp://if0_38268624@ftpupload.net
Zjy63yEvODsfxX

grep -rnIF "layout.topic" ./ --exclude-dir={.git}
grep -rlIF "layout.topic" ./ --exclude-dir={.git} \
  | xargs sed -i 's/layout\.topic/layout.Topic/g'

- work with fetch with loader like pdf js do
- file drag n drop
- update setDynamicInput library,setPrompt,object to table library
- create carousel component in markdown
- sync class attribute of content with doc
- area.ai is inspiration
- switch tab to toggle content rendered content
- create toc for topic and markdown and render while reading mode
- adjust topic section column width
- 
- add .no-prs class to remove unwanted element while presentation
- store each topic as a tab to work on dual
- prefer cyan light blue bg and white as section bg
- topic container height  = window.innerheight - header.clientHeight
- change github like logo for qodc like fa-book-open
- alt+1/2/3/4 to open category,subject,chapter,topic list to switch prompt
- save last repo
- userRepo.fileExist() will be userRepo.has()
- categoryFiled text truncate
- uploaing file prompt box
- update prompt with file upload and input event
- prompt textarea height fix
- import {#segment} from './topic'
- shortcut to create new chapter and topic by pressing n command
- Implement CLI framework
- make topic,chapter from list
- gray 500 outline color
- a media folder that store all the file content because the subject delete clone and alter link inside it
- filedeck.live like our project
- https://01a1c0de-293c-7815-bc04-ffc77dea78cd.arena.site/ ui inspiration
- https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh searchbar bg
- https://cinejoy.pk/ inspirational Ui
- https://sitesblocked.com/status/vercel.app/blocked-in/bangladesh page theme inspiration
- https://www.innateblogger.com/p/markdown-to-pdf.html (greate inspiration of aesthetic document) like our project
- colorpie white bg 
- claude and sublime dark layout
- no padding in highlight text just light yellow bg
- close process box after process complete,create new userRepo event onProcessComplete()
- file move functionality
- asynchrnous file operations
- using relative path in image
- any subject,chapter,topic starts with . will be hidden by default
- create a .share folder to share any topic wihtout knowing it chapter,topic,etc
- add .gap.topic to separate topic section in the sidebar
- how we able to authenticate with wrong token,checkout this
- move all .md file into info/
- add benchmark or testing list before send to production
- ubuntu style file manager header
- handle edit new line issue
- QDoc application idea
- add scroll to code block
- import topic logic and embed them in our topic
- gemini like file view section
- whatsapp like dropdown scale animation 
- linux filemanager like filemanager
- no select and recursive of it
doc.create ,commit msg should include path not the url

### Current Target
- show userrepo response error
- ubuntu like slideshow image vierwer
- link prompt
- doc.dir{path,current.file,folder,content,download_link,etc}
- screenshot of a content
- show toc for non-user at the top
- move leftcanvas to top header
- terminal
- code editor 
- set toast html instead of text
- handle qdoc redirection
- handle edit btn if user is not author
- handle search result


Branches of QDoc

### inspiration
- https://fildos.ahmedfahim.dev/ inspiration
- https://portable-linux-apps.github.io/en/app/5ire.html inspiratio for dark mode
- tabler.io for bg and dialog 
- jsdelivr for for
- pagefind.app 
- sheperdjs.dev
- floating-ui.com

### Ui and Layout
- https://catppuccin.com/ best of all
- https://cherryai.com/ inspiration
- https://filedeck.live/ inspiration
- use this font Bricolage+Grotesque
- https://github.com/features/code-search see search layout
- github like secondary btn
- backbtn list item rounded-0 and bg-body-tertiary
- topic container p-0 p-lg-2 pt-lg-0
- ms work style edit btns for config
- add reverse option in topic
- change default theme based on time
- inspiration 
- https://cursor.com/docs
- https://7inif7p6jcz2y.kimi.page/?id=2079217808532901888&share_id=19f7fd7e-2022-8739-8000-000014716a87
- https://www.kimi.com/code?from=kimi_homepage_sidebar

- follow kimi.com webpage layout
- hide scroll on hover in file view pane
- tab active btn match pane bg
- enter full screen dialog on mobile device
- improve file viewer pane
- copy kde type notification prompt layout

- google chrome like profile menu
- chatgpt like minimize,maximize animation
- love this website tab,button font https://terminaltrove.com/ad/
- cover all css variable to change page theme
- cover all css variable to change content theme
- handle layout on print
- notebook llm type presentation theme check 
- set up testing doc content
- set up testing
- drag and drop file in upload pane

### Auth
- fix register auth
- copy token by giving password
- handle password and token auth
- handle message after login and register successfull


### Doc
- github like markdown view and tab and toc
- add ignore folder names option in config
- copy file source after uploaded
- doc encoding on file rename if file is topic else ignore encoding
- work with pdf
- add markdown as a topic type file
- any subject,chapter,topic starts with . will be hidden by default
- create a .share folder to share any topic wihtout knowing it chapter,topic,etc
- add .gap.topic to separate topic section in the sidebar
- show commit list of file and load commit history of that file
- load cache of commits and search result for preview
- improve searching same text again
- introduce new features bookmark(folder) like linking topic to quick access frequece topic
- fix path handling in production
- change topic icon of searched topic
- work on redirect and segment # in url
- add big random number of chapter load
- handle quickNote
- Add pdf,doc,docs,link as a topic
- handle loading topic based on file extension
- load related topic and author details in a more proper way
- create a function that can open any topic as a prompt
- create wikipedia style bar that show overall page heading and table of content
- show author details in a prompt by .author file in root directory
- show subject,chapter details in same manner
- handle .config file root,subject,chapter directory for content configuration nested
  like hide folder,set icon,sorting order,
- search content prompt follow responsive width
- no space in config tags
- handle markdownit library and plugin with doc


### Content
- on presentation sibling element got lower opacity to highligh current element
- set img link,diagram link,slideshow etc opening
- dual view
- notes saving
- 
- test outfit as header font
- https://dm.terabox.com/pfile/docview?path=%2FTeraBoxQuickStartGuide.pdf&client=web&scene=main set this website bg and section
- prefer header font 'Linux Libertine', 'Georgia', 'Times', 'Source Serif 4', serif;
- Github like toc
- improve screenshot functionality of certain component like gofullpage chrome extension
- details has left bar
- linux like image viewer
- set braeak:true in markdownIt library
- https://onecompiler.com/bootstrap#draft-4njq use as compiler 
- undeline,strong,bold etc font-size set .9em and .katex get normal 1em KaTeX_Main,Times New Roman,serif
- a combo of line height 1.7 and font Tribuchet Ms
- change font to Verdana,'Tribuchet Ms,Lexend
- light hr tag color,table etc follow markdown-it.github.io
- https://markdown-it.github.io/ use this website as editor
- add edit prompt for attribute
- fix table bg and set stripped
- store last saved changes from redo_undo memory to localstorage
- test color
- add different color in note
- add new shortcut for highlight element
- test font family loading
- set up preference toolbox functionality
- add sublime based filename prompt to edit content
- improve presentation animation and transition
- enable focus mode in presentation that show only that element and hide all previous and next element
- and alt+f show previous element again
- handle content on print
- reset content shortcut
- italic light image text


### Library
- show log concept window.logs a object that store all printable data during operations
- add new php,js,css,html library by learning 
- find new javascript,css libaray
- list of popular and needed library
