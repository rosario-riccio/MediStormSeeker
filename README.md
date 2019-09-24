# MediStormSeeker

This software allows to identify different sensitive weather event in the Mediterranean Sea; in fact you will be able to locate a storm with a specific polygon. This polygon will have its own pop-up where insert a specific weather label.

Installation:
It is necessary to install mongodb and create a collection for users with unique username:
you type this command "db.UserCollection.createIndex( { "username": 1 }, { unique: true } )"
