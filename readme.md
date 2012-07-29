# Middleman-Foundation-Haml-template

This is a simple template to get started with Middleman 3.0, Zurb Foundation 3.0 and Haml as template language.

To get started you need middleman:
```bash
gem install middleman
```

Copy this template to ~/.middleman/foundation

```bash
mkdir ~/.middleman
cd ~/.middleman
git clone git://github.com/steen919/middleman-foundation-haml-template.git
```

Create a new middleman project in a folder of your choosing (I use ~/dev for my devs...)

```bash
cd ~/dev
middleman init <new_project_name> --template=middleman-foundation-haml-template
cd ~/dev/<new_project_name>
bundle install
```

Start server (open in web browser at localhost:4567)

```bash
bundle exec middleman server
```

Stop server with ctrl-c
