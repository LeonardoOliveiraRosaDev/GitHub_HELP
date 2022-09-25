Quando der esse erro !

fatal: detected dubious ownership in repository at 'D:/....................................'
To add an exception for this directory, call:

        git config --global --add safe.directory 'D:/....................................'

Set the environment variable GIT_TEST_DEBUG_UNSAFE_DIRECTORIES=true and run
again for more information.



Use esse codigo abaixo para resolver

git config --global --add safe.directory '*'



