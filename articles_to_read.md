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

- More: https://github.com/keplerproject/luarocks/wiki/Documentation#Presentations

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