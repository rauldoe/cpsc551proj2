https://github.com/rauldoe/cpsc551proj2 


pip3 install --user PyYAML

gem install foreman


clear; ruby tuplespace.rb -c alice.yaml
clear; ruby adapter.rb -c alice.yaml

clear; ruby tuplespace.rb -c bob.yaml
clear; ruby adapter.rb -c bob.yaml

clear; ruby tuplespace.rb -c chuck.yaml
clear; ruby adapter.rb -c chuck.yaml

clear; python subscribe.py 127.0.0.1 54321