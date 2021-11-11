# cheatsheets
GIT:

git config --global user.name 'your_username'

git config --global user.email 'your_email_address@example.com'

git config --global --list


Check all checkboxes on page in chrome dev console:
$$('input[type="checkbox"').map(i => i.checked = true)

Add to every bashscript:
IFS="$(printf '\n\t')"
# or:
IFS="`printf '\n\t'`"
# Widely supported, POSIX added http://austingroupbugs.net/view.php?id=249
IFS=$'\n\t'
