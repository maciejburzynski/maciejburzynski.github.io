---
title: "Eluwina byku"
layout: posts
date:   2023-12-26 20:52:10 +0100
categories:
  - Edge Case
tags:
  - content
  - css
  - edge case
  - lists
  - markup
---

Nested and mixed lists are an interesting beast. It's a corner case to make sure that

* Lists within lists do not break the ordered list numbering order
* Your list styles go deep enough.

### Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item 
   * **unordered**
   * **unordered** 
     1. ordered item
     2. ordered item
3. ordered item
4. ordered item

### Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item 
   * **unordered**
   * **unordered** 
     * unordered item
     * unordered item
3. ordered item
4. ordered item

### Unordered -- Ordered -- Unordered

* unordered item
* unordered item 
  1. ordered
  2. ordered 
     * unordered item
     * unordered item
* unordered item
* unordered item

### Unordered -- Unordered -- Ordered

* unordered item
* unordered item 
  * unordered
  * unordered 
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item

### Task Lists

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
























                                                                                      [ Read 38 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
     Build Warning: Layout 'page' requested in about.markdown does not exist.
                    done in 5.822 seconds.
 Auto-regeneration: enabled for '/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
[2024-02-15 21:51:49] ERROR `/favicon.ico' not found.
^X^Z
[2]+  Zatrzymano              bundle exec jekyll serve
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -n '1st after revert'
error: pathspec '1st after revert' did not match any file(s) known to git
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 38 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
Everything up-to-date
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m '1st after revert'
[itempotentni-prod d8c3162] 1st after revert
 2 files changed, 1 insertion(+), 2 deletions(-)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 485 bytes | 485.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   9ca62af..d8c3162  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ bundle
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Could not find compatible versions

Because github-pages >= 228, < 229 depends on jekyll = 3.9.3
  and Gemfile depends on jekyll ~> 3.9.5,
  github-pages >= 228, < 229 cannot be used.
So, because Gemfile depends on github-pages ~> 228,
  version solving has failed.
MacBook-Air-maciejburzynski:docs maciejburzynski$ ls
404.html	CNAME		Gemfile		Gemfile.lock	_config.yml	_posts		_site		about.markdown	index.markdown
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ bundle
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Using bigdecimal 3.1.6 (was 3.1.5)
Using minitest 5.22.2 (was 5.20.0)
Using gemoji 4.1.0 (was 3.0.1)
Using public_suffix 5.0.4 (was 4.0.7)
Using coffee-script-source 1.12.2 (was 1.11.1)
Using rouge 3.30.0 (was 3.26.0)
Using kramdown 2.4.0 (was 2.3.2)
Using activesupport 7.1.3 (was 7.1.2)
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 38 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
Using faraday-net_http 3.1.0 (was 3.0.2)
Using jekyll-coffeescript 1.2.2 (was 1.1.1)
Using nokogiri 1.16.2 (x86_64-darwin) (was 1.15.5)
Using faraday 2.9.0 (was 2.8.1)
Using jekyll 3.9.5 (was 3.9.3)
Using jekyll-feed 0.17.0 (was 0.15.1)
Using jekyll-avatar 0.8.0 (was 0.7.0)
Using jekyll-default-layout 0.1.5 (was 0.1.4)
Using jemoji 0.13.0 (was 0.12.0)
Using github-pages-health-check 1.18.2 (was 1.17.9)
Using jekyll-github-metadata 2.16.1 (was 2.13.0)
Using github-pages 231 (was 228)
Bundle complete! 9 Gemfile dependencies, 97 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'aaaa'
[itempotentni-prod d9ca4fc] aaaa
 2 files changed, 45 insertions(+), 42 deletions(-)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 924 bytes | 924.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 38 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   d8c3162..d9ca4fc  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ ls
404.html	CNAME		Gemfile		Gemfile.lock	_config.yml	_posts		_site		about.markdown	index.markdown
MacBook-Air-maciejburzynski:docs maciejburzynski$ cd _site/
MacBook-Air-maciejburzynski:_site maciejburzynski$ ls
404.html	about		assets		feed.xml	index.html	jekyll
MacBook-Air-maciejburzynski:_site maciejburzynski$ ls -l
total 48
-rw-r--r--  1 maciejburzynski  staff  4639 15 lut 21:51 404.html
drwxr-xr-x@ 3 maciejburzynski  staff    96 15 lut 21:51 about
drwxr-xr-x@ 4 maciejburzynski  staff   128 15 lut 21:51 assets
-rw-r--r--  1 maciejburzynski  staff  4423 15 lut 21:51 feed.xml
-rw-r--r--  1 maciejburzynski  staff  5063 15 lut 21:51 index.html
drwxr-xr-x@ 3 maciejburzynski  staff    96 15 lut 21:51 jekyll
MacBook-Air-maciejburzynski:_site maciejburzynski$ cd jekyll/
MacBook-Air-maciejburzynski:jekyll maciejburzynski$ ls
update
MacBook-Air-maciejburzynski:jekyll maciejburzynski$ cd update/
MacBook-Air-maciejburzynski:update maciejburzynski$ ls
2023
MacBook-Air-maciejburzynski:update maciejburzynski$ cd ../..
MacBook-Air-maciejburzynski:_site maciejburzynski$ ls
404.html	about		assets		feed.xml	index.html	jekyll
MacBook-Air-maciejburzynski:_site maciejburzynski$ cd ..
MacBook-Air-maciejburzynski:docs maciejburzynski$ ls
404.html	CNAME		Gemfile		Gemfile.lock	_config.yml	_posts		_site		about.markdown	index.markdown
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 38 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'version bump'
[itempotentni-prod 3beb0ca] version bump
 1 file changed, 1 insertion(+), 1 deletion(-)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 388 bytes | 388.00 KiB/s, done.
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 56 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   d9ca4fc..3beb0ca  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ gem "minimal-mistakes-jekyll"
ERROR:  While executing gem ... (Gem::UnknownCommandError)
    Unknown command minimal-mistakes-jekyll
	/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/command_manager.rb:205:in `find_command'
	/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/command_manager.rb:250:in `invoke_command'
	/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/command_manager.rb:192:in `process_args'
	/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/command_manager.rb:150:in `run'
	/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/gem_runner.rb:51:in `run'
	/Users/maciejburzynski/.rbenv/versions/3.2.2/bin/gem:10:in `<main>'
MacBook-Air-maciejburzynski:docs maciejburzynski$ bundle update
Fetching gem metadata from https://rubygems.org/..........
Resolving dependencies...
Using concurrent-ruby 1.2.3 (was 1.2.2)
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 40 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
Bundle updated!
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ bundle
Fetching gem metadata from https://rubygems.org/.........
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 56 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
Resolving dependencies...
Fetching minimal-mistakes-jekyll 4.24.0
Installing minimal-mistakes-jekyll 4.24.0
Bundle complete! 10 Gemfile dependencies, 98 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
MacBook-Air-maciejburzynski:docs maciejburzynski$ ls
404.html	CNAME		Gemfile		Gemfile.lock	_config.yml	_posts		_site		about.markdown	index.markdown
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'version bump'
[itempotentni-prod 1f2b1d3] version bump
 2 files changed, 12 insertions(+), 2 deletions(-)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 628 bytes | 628.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   3beb0ca..1f2b1d3  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ ls
404.html	CNAME		Gemfile		Gemfile.lock	_config.yml	_posts		_site		about.markdown	index.markdown
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ bundle install
Bundle complete! 10 Gemfile dependencies, 98 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$  bundle exec jekyll serve
Configuration file: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
            Source: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs
       Destination: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
      Remote Theme: Using theme mmistakes/minimal-mistakes
       Jekyll Feed: Generating feed for posts
     Build Warning: Layout 'post' requested in _posts/2023-12-25-welcome-to-jekyll.markdown does not exist.
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
     Build Warning: Layout 'page' requested in about.markdown does not exist.
                    done in 7.119 seconds.
 Auto-regeneration: enabled for '/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs'
jekyll 3.9.5 | Error:  Address already in use - bind(2) for 127.0.0.1:4000
/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:205:in `bind': Address already in use - bind(2) for 127.0.0.1:4000 (Errno::EADDRINUSE)
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:205:in `listen'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:768:in `block in tcp_server_sockets'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:231:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:231:in `foreach'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:766:in `tcp_server_sockets'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/utils.rb:60:in `create_listeners'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/server.rb:130:in `listen'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/server.rb:111:in `initialize'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/httpserver.rb:47:in `initialize'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:229:in `new'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:229:in `start_up_webrick'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:104:in `process'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:93:in `block in start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:93:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:93:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/exe/jekyll:15:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/jekyll:25:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/jekyll:25:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:58:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:58:in `kernel_load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:23:in `run'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:492:in `exec'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/command.rb:28:in `run'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor.rb:527:in `dispatch'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:34:in `dispatch'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/base.rb:584:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:28:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/exe/bundle:37:in `block in <top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/friendly_errors.rb:117:in `with_friendly_errors'
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 56 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/exe/bundle:29:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/bundle:25:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/bundle:25:in `<main>'
MacBook-Air-maciejburzynski:docs maciejburzynski$ kill -9  $(lsof -t -i:4000)
[2]+  Killed: 9               bundle exec jekyll serve
MacBook-Air-maciejburzynski:docs maciejburzynski$ kill -9  $(lsof -t -i:4000)
kill: składnia: kill [-s sygnał | -n numer-sygnału | -sygnał] pid | zadanie ... lub kill -l [sygnał]
MacBook-Air-maciejburzynski:docs maciejburzynski$  bundle exec jekyll serve
Configuration file: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
            Source: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs
       Destination: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
      Remote Theme: Using theme mmistakes/minimal-mistakes
       Jekyll Feed: Generating feed for posts
     Build Warning: Layout 'post' requested in _posts/2023-12-25-welcome-to-jekyll.markdown does not exist.
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
     Build Warning: Layout 'page' requested in about.markdown does not exist.
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 40 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
                    done in 6.364 seconds.
 Auto-regeneration: enabled for '/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
[2024-02-18 12:42:28] ERROR `/favicon.ico' not found.
^X^Z
[2]+  Zatrzymano              bundle exec jekyll serve
MacBook-Air-maciejburzynski:docs maciejburzynski$ kill -9  $(lsof -t -i:4000)
[2]+  Killed: 9               bundle exec jekyll serve
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$  bundle exec jekyll serve
Configuration file: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
            Source: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs
       Destination: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_site
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 57 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
 Incremental build: disabled. Enable with --incremental
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 40 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
      Generating...
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 57 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
      Remote Theme: Using theme mmistakes/minimal-mistakes
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 56 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
       Jekyll Feed: Generating feed for posts
     Build Warning: Layout 'post' requested in _posts/2023-12-25-welcome-to-jekyll.markdown does not exist.
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
     Build Warning: Layout 'page' requested in about.markdown does not exist.
                    done in 5.979 seconds.
 Auto-regeneration: enabled for '/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
^X^Z
[2]+  Zatrzymano              bundle exec jekyll serve
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'add theme'
[itempotentni-prod 30ac959] add theme
 1 file changed, 1 insertion(+)
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 56 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 415 bytes | 415.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   1f2b1d3..30ac959  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano Gemfile
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'remove theme; switch to dark theme'
[itempotentni-prod b9342b8] remove theme; switch to dark theme
 1 file changed, 1 insertion(+), 2 deletions(-)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 437 bytes | 437.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   30ac959..b9342b8  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'add subpath'
[itempotentni-prod 853cb55] add subpath
 1 file changed, 2 insertions(+)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 405 bytes | 405.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/maciejburzynski/maciejburzynski.github.io.git
   b9342b8..853cb55  itempotentni-prod -> itempotentni-prod
MacBook-Air-maciejburzynski:docs maciejburzynski$ bundle install
Bundle complete! 10 Gemfile dependencies, 98 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
MacBook-Air-maciejburzynski:docs maciejburzynski$ git status
On branch itempotentni-prod
Your branch is up to date with 'origin/itempotentni-prod'.

nothing to commit, working tree clean
MacBook-Air-maciejburzynski:docs maciejburzynski$  bundle exec jekyll serve
jekyll 3.9.5 | Error:  (/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml): did not find expected key while 
parsing a block mapping at line 20 column 1
/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/psych/parser.rb:62:in `_native_parse': (/Users/maciejburzynski/Desktop/Biurko — MacBook Air 
(maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml): did not find expected key while parsing a block mapping at line 20 column 1 (Psych::SyntaxError)
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/psych/parser.rb:62:in `parse'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:143:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:157:in `block in load_file'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:157:in `open'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:157:in `load_file'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/configuration.rb:143:in `safe_load_file'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/configuration.rb:180:in `read_config_file'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/configuration.rb:207:in `block in read_config_files'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/configuration.rb:205:in `each'
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 58 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/configuration.rb:205:in `read_config_files'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll.rb:113:in `configuration'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/command.rb:43:in `configuration_from_options'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:89:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/exe/jekyll:15:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/jekyll:25:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/jekyll:25:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:58:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:58:in `kernel_load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:23:in `run'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:492:in `exec'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/command.rb:28:in `run'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor.rb:527:in `dispatch'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:34:in `dispatch'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/base.rb:584:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:28:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/exe/bundle:37:in `block in <top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/friendly_errors.rb:117:in `with_friendly_errors'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/exe/bundle:29:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/bundle:25:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/bundle:25:in `<main>'
MacBook-Air-maciejburzynski:docs maciejburzynski$ nano _config.yml
MacBook-Air-maciejburzynski:docs maciejburzynski$  bundle exec jekyll serve
Configuration file: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
            Source: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs
       Destination: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
      Remote Theme: Using theme mmistakes/minimal-mistakes
       Jekyll Feed: Generating feed for posts
     Build Warning: Layout 'post' requested in _posts/2023-12-25-welcome-to-jekyll.markdown does not exist.
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
     Build Warning: Layout 'page' requested in about.markdown does not exist.
                    done in 6.035 seconds.
 Auto-regeneration: enabled for '/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs'
jekyll 3.9.5 | Error:  Address already in use - bind(2) for 127.0.0.1:4000
/Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:205:in `bind': Address already in use - bind(2) for 127.0.0.1:4000 (Errno::EADDRINUSE)
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:205:in `listen'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:768:in `block in tcp_server_sockets'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:231:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:231:in `foreach'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/3.2.0/socket.rb:766:in `tcp_server_sockets'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/utils.rb:60:in `create_listeners'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/server.rb:130:in `listen'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/server.rb:111:in `initialize'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/webrick-1.8.1/lib/webrick/httpserver.rb:47:in `initialize'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:229:in `new'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:229:in `start_up_webrick'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:104:in `process'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:93:in `block in start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:93:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:93:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.5/exe/jekyll:15:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/jekyll:25:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/jekyll:25:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:58:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:58:in `kernel_load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli/exec.rb:23:in `run'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:492:in `exec'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/command.rb:28:in `run'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor.rb:527:in `dispatch'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:34:in `dispatch'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/vendor/thor/lib/thor/base.rb:584:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/cli.rb:28:in `start'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/exe/bundle:37:in `block in <top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/lib/bundler/friendly_errors.rb:117:in `with_friendly_errors'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.22/exe/bundle:29:in `<top (required)>'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/bundle:25:in `load'
	from /Users/maciejburzynski/.rbenv/versions/3.2.2/bin/bundle:25:in `<main>'
MacBook-Air-maciejburzynski:docs maciejburzynski$ kill -9  $(lsof -t -i:4000)
MacBook-Air-maciejburzynski:docs maciejburzynski$  bundle exec jekyll serve
Configuration file: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
            Source: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs
       Destination: /Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
      Remote Theme: Using theme mmistakes/minimal-mistakes
       Jekyll Feed: Generating feed for posts
     Build Warning: Layout 'post' requested in _posts/2023-12-25-welcome-to-jekyll.markdown does not exist.
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
     Build Warning: Layout 'page' requested in about.markdown does not exist.
                    done in 5.78 seconds.
 Auto-regeneration: enabled for '/Users/maciejburzynski/Desktop/Biurko — MacBook Air (maciejburzynski)/Repos/maciejburzynski.github.io/docs'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
[2024-02-18 12:54:07] ERROR `/favicon.ico' not found.
^X^Z[2]   Killed: 9               bundle exec jekyll serve

[3]+  Zatrzymano              bundle exec jekyll serve
MacBook-Air-maciejburzynski:docs maciejburzynski$ git ad .
git: 'ad' is not a git command. See 'git --help'.
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 29 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell

The most similar commands are
	add
	aa
	ac
	am
	au
MacBook-Air-maciejburzynski:docs maciejburzynski$ git add .
MacBook-Air-maciejburzynski:docs maciejburzynski$ git commit -m 'correct colon'
[itempotentni-prod 0de55f0] correct colon
 1 file changed, 1 insertion(+), 1 deletion(-)
MacBook-Air-maciejburzynski:docs maciejburzynski$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 383 bytes | 383.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
  UW PICO 5.09                                                                                 New Buffer


























                                                                                      [ Read 29 lines ]
^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
  UW PICO 5.09                                                                 File: 2023-12-25-welcome-to-jekyll.markdown

---
layout: post
title:  "Welcome to Jekyll!"
date:   2023-12-25 20:52:10 +0100
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common 
way i$

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the 
nece$

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have 
questions, you$

^G Get Help                    ^O WriteOut                    ^R Read File                   ^Y Prev Pg                     ^K Cut Text                    ^C Cur Pos
^X Exit                        ^J Justify                     ^W Where is                    ^V Next Pg                     ^U UnCut Text                  ^T To Spell
