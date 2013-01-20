# Liftr Registry is a Bower Server

## Create package

    curl http://liftr-registry.theblacksmithhq.com/packages -v -F 'name=jquery' -F 'url=git://github.com/jquery/jquery.git'

or

    liftr register jquery jquery/jquery

## Find package

    curl http://liftr-registry.theblacksmithhq.com/packages/jquery
      {"name":"jquery","url":"git://github.com/jquery/jquery.git"}

OR

    liftr search jquery

## License

Copyright 2012 Twitter, Inc.

Licensed under the MIT License
