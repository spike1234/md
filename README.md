md
--------------------

markdown test


some code:

	local coso = 'http://sports.espn.go.com/nba/bottomline/scores'
	local response = http.request {
		url = coso
	}
	
	return response.content --, {["Content-Type"]="text/xml"}




# Hello world!
This is written with **[dillinger.io][1]**.

[1]: dillinger.io

