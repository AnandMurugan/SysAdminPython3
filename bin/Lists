#!/usr/bin/env python3.7

users = [{'admin':False, 'active':False, 'name':'Kevin'},
        {'admin':True, 'active':True, 'name':'Kavin'},
        {'admin':True, 'active':False, 'name':'John'},
        {'admin':False, 'active':True, 'name':'Sam'}]
line = 1
for user in users:
    prefix = ''

    if user['active'] and user['admin']:
        prefix += 'ACTIVE - (ADMIN) '
    elif user['active']:
        prefix += 'ACTIVE - '
    elif user['admin']:
        prefix += '(ADMIN) '


    print(f'{line} ' + prefix + '%s' % (user['name']))
    line += 1

