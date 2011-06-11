# What's this ?

sample application for saving has_many relations.

In this application, Post has_many Tags through Taggings.
When you save tagged post via web interface, taggings are automatically saved.
It uses accepts_nested_attributes_for and fields_for.

See more on API references:

* http://api.rubyonrails.org/classes/ActiveRecord/NestedAttributes/ClassMethods.html
* http://api.rubyonrails.org/classes/ActionView/Helpers/FormHelper.html#method-i-fields_for


# How to run ?

* bundle
* rake db:migrate
* rails server
* open http://localhost:3000/tags and create tags
* open http://localhost:3000/posts and create posts


# How to create erd diagram ?

* install some softwares along http://rails-erd.rubyforge.org/install.html
* rake erd attributes=foreign_keys,timestamps,inheritance,content
* open ERD.pdf

