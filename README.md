# SYNOPSIS

Fetch remote file using http.

# INSTALL

    $ panda install Sparrowdo::RemoteFile

# USAGE

    $ cat sparrowfile

    module_run 'RemoteFile', %(
        url       => 'https://github.com/melezhik/remote-file/archive/master.zip',
        location  => '/tmp/foo/bar/master.zip'
    );
    

# Parameters

## url

Remote file url. No default value. Obligatory.

## location

A local file path where to store a downloaded file. No default value. Obligatory.
  
# Author

[Alexey Melezhik](melezhik@gmail.com)
