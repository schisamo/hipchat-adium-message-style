# HipChat Adium Message Style

Makes Adium look like HipChat...without all that nasty Adobe Air memory bloat. :)

Pairs quite nicely with the [HipChat emoticon set for Adium](https://github.com/thepaul/adium-hipchat-emoticons).

# Installation

Clone the repo and symlink `HipChat.AdiumMessageStyle` to Adium's `Message Styles`
folder:

    ln -s ~/dev/code/hipchat-adium-message-style/HipChat.AdiumMessageStyle ~/Library/Application\ Support/Adium\ 2.0/Message\ Styles/HipChat.AdiumMessageStyle

# Configuration

Go to **Adium** => **Preferences** => **Messages**.  Find the **Message Style** dropdown and select **HipChat**.

# Features

* Full message theming insipired by HipChat's official style sheet
* Proper hyperlinking of system messages...things like GitHub [commit messages](http://blog.hipchat.com/2010/05/25/github-adds-hipchat-support/).
* Proper formatting of [@ mentions](https://www.hipchat.com/help/page/how-do-mentions-work)
* Accurate coloring of most system messages..ie Github, Jenkins etc.

Coming Soon:

* Inline previews for images
* Inline previews for YouTube videos
* Make system message => color mapping configurable

# Author

Seth Chisamore (<schisamo@gmail.com>)

Copyright (c) 2012 Seth Chisamore

# License

License:: Apache License, Version 2.0

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
