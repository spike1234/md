md
--------------------

markdown test


some code:

	local coso = 'http://sports.espn.go.com/nba/bottomline/scores'
	local response = http.request {
		url = coso
	}
	
	return response.content --, {["Content-Type"]="text/xml"}


------------------------


code inline: `if 1 = 1 then`
some `code`

	if 1 = 1 then
		' sadfsdfiuosdf
	else
		'other
	end if
	

# Hello world!
This is written with **[dillinger.io][1]**.

[1]: dillinger.io

