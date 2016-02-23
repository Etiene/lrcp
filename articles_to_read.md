#Articles to read

#Critics on language specific package managers
 - Language Specific Package Managers, by Kevin Cox, 18/10/2013, accessed 22/02/2016  https://kevincox.ca/2013/10/18/language-specific-package-managers/

###Summarized:
Language specific package managers are needed because authors need an easy way of publishing, but they are problematic for updating, integrating with your system and some of them don't have many features. A recurrent problem with maintaining packages is authors not abiding to semantic versioning. 

#Comparison of tools
- Which programming language has the best package manager?, by Robert Reiz, 15/01/2014, accessed 22/02/2016 http://blog.versioneye.com/2014/01/15/which-programming-language-has-the-best-package-manager/
	- Discussion on reddit: https://www.reddit.com/r/programming/comments/1vg4q0/which_programming_language_has_the_best_package/

###Summarized:
####What's a package manager
A developer tool that allows to easily publish and consume software libraries and manage dependencies. The package manager:
- Has a repository of binaries or source code
- Has a client, usually a command-line tool, that communicates with the repository
- Downloads the libraries from the repository
- Places the library in the right place and links them to the repository
- Resolves dependencies
####Compares package managers on the following properties
- Packages are signed
- Has a centralized repository
- This repository has mirrors
- Learning curve and easiness of use
- Semver support
- Mandatory license
- Documentation

--> It does not mention their web interfaces


#LuaRocks
- LuaRocks - a declarative and extensible package management system for Lua, by Hisham Muhammad, Fabio Mascarenhas, Roberto Ierusalimschy, 17th Brazilian Symposium, SBLP 2013, accessed 22/02/2016   http://www.inf.puc-rio.br/~roberto/docs/sblp2013-2.pdf

###Summarized:
Argues that language-specific package managers are intrinsically linked to the language design of the language they were built for. How modules are built, packaged, deployed, detected depend on decisions of implementation particular of each language. Example: In languages that require a compilation step, the package manager has to deal with that. LuaRocks is a language-specific package manager for the Lua programming language. Lua only gained a module feature on v5.0, 10 years after the initial release of the language, and with it, new concerns about namespacing, build methods, packaging formats and redistribution of modules. Because Lua's goal is to remain minimal for being embeddable, it would not deal with it internally. 

Important to note: OS package managers are more mature. 

- More: https://github.com/keplerproject/luarocks/wiki/Documentation#Presentations

#Programming language adoption & Lua adoption
- https://news.ycombinator.com/item?id=3746692
- http://www.sitepoint.com/whats-best-programming-language-learn-2015/
- http://readwrite.com/2012/06/05/5-ways-to-tell-which-programming-lanugages-are-most-popular
- http://www.itjobswatch.co.uk/jobs/uk/lua.do
- http://www.ryan-williams.net/hacker-news-hiring-trends/2016/february.html?compare1=Lua&compare2=&compare3=&compare4=
- http://pypl.github.io/PYPL.html
- http://githut.info/
- Tiobe Index: https://web.archive.org/web/20120404133905/http://www.tiobe.com/content/paperinfo/tpci
	- Feb 2016: Java #1, C #2, C++ #3, Python #5, PHP, #6, Perl #8, JS #9, Ruby #11, COBOL #22, Dart #28, Lua #32, Go #38, Haskell #40, Rust #48
	- Mar 2015: 1: C, Java, C++, 6: JS, PHP, Python, 12: Perl, 20: Ruby, 22: COBOL, 40:lua, 43: go, 46: haskell
	- Mar 2014: 1:C, Java, 4: C++, 6: PHP, 8: Python, JS, 13: Perl, Ruby, 30: COBOL, 33: Lua, 36: Go, 49: Haskell
	- Mar 2013: 1: Java, C, 4: C++, 6: PHP, 8: Python, Ruby, Perl, JS, 19: Lua, 26: COBOL, 32: Haskell
	- Mar 2012: 


- Leo A. Meyerovich (UC Berkeley), Ariel Rabkin (Princeton University). Empirical  Analysis  of  Programming  Language  Adoption, OOPSLA 2013, accessed Feb 23 2016. http://sns.cs.princeton.edu/docs/asr-oopsla13.pdf

What  statistical  properties  describe  language  popularity? empirical  analysisof  language  use  across  many  open  source  projects.

"One  consequence  of  these  findings,  taken  together,  isthat  language  designers  and  advocates  should  emphasizelibraries.  It  is  easy  to  find  anecdotal  examples  of  librariesthat had major influence on language adoption within niches,such asnumpyfor numerical programming in Python, andRuby on Rails for web applications"

Top 1 factor for picking a language: open source libraries


- Why Lua is not more popular, a discussion at the Lua mail list: http://lua-users.org/lists/lua-l/2013-09/msg00321.html

What is popular and what is trendy? Lua IS popular, it's used in the UI of every amazon kindle, but do people know that?
Lua users are generally scared of what will become of Lua if it inflates. We tend to consider Lua our special rare gem. 
The discussion seemed to derail and went to discuss C bindings and how to use Lua, instead of fostering the ecosystem of open source libs.

An interesting perspective is that users tend believe there is a conflict between the "batteries not included" philosophy of Lua, its simplicity, and it ever becoming popular as a general use language. But there is not. 

- Panel: The future of small languages, Andy Wingo, Christopher Webber, Ludovic Courtès, Hisham Muhammad, Etiene Dalcol, Julien Danjou FOSDEM 2016 https://fosdem.org/2016/schedule/event/future_guile_lua/

- The state of the Lua ecosystem. Pierre Chapuis, Lua Workshop 2015 http://www.lua.org/wshop13/Chapuis.pdf

- https://news.ycombinator.com/item?id=3534746

- How lua became popular at game dev: a historical anecdote on community: https://www.quora.com/How-did-Lua-become-popular-in-the-video-game-industry

- Why isn't lua more widely used, a discussiona at lua-list: http://lua.2524044.n2.nabble.com/Why-isn-t-Lua-more-widely-used-td7232180.html


#User experience design
- https://en.wikipedia.org/wiki/User_experience_design
- http://uxmyths.com/
- https://www.usertesting.com/blog/2015/09/16/what-is-ux-design-15-user-experience-experts-weigh-in/
- https://www.academia.edu/19730927/Web_Writing_with_the_User_in_Mind
- https://opensource.com/life/15/3/user-experience-open-source-future
- https://opensource.com/life/14/1/how-to-leverage-user-design
- https://www.nngroup.com/articles/ten-usability-heuristics/
- http://atmire.com/website/?q=content/open-source-user-experience-design-fosdem
- http://firstmonday.org/ojs/index.php/fm/article/viewArticle/1018
- https://www.academia.edu/19658710/Barata_Jo%C3%A3o_Miguel_Rui_Ribeiro_Liliana_Pereira_Madalena_Lucas_Jos%C3%A9_The_culture_of_obstacles_-_design_for_the_user_s_experience_p._669-674_._ICDHS_2014_-_9th_ICDHDS._S%C3%A3o_Paulo_Blucher_2014._ISSN_2318-6968_DOI_10.5151_despro-icdhs2014-0098
- http://www.linuxjournal.com/content/its-about-user-applying-usability-open-source-software
- http://people.lis.illinois.edu/~twidale/research/ossui/