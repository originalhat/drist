# github api calls


## list gists

	$ curl -u dgbsco https://api.github.com/gists

## list starred gists

	$ curl -u dgbsco https://api.github.com/gists/starred

## list all gists (annoyn)

	$ curl https://api.github.com/users/dgbsco/gists

## specific gist

	$ curl https://api.github.com/gists/99490c004e8e82ebcb1a

## post a gist

	$ curl -d '{"public":true,"files":{"test.txt":{"content":"String file contents"}}}' https://api.github.com/gists https://api.github.com/users/dgbsco/gists