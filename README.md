#Branches mit den grundlegenden Git-Kommandos

##Start

    $ git init
    $ git commit --allow-empty -m 'initialer Commit'
    $ git checkout -v develop master

##Feature entwickeln 

    $ git checkout -b feature/<Name> develop

##Feature teilen

    $ git checkout feature/<Name>
    $ git push origin feature/<Name>
