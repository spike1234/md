markdown tests
--------------------

una tabella!

| Arma                | DannoDa  | DannoA  | Note      |
| ------------------- | -------- | ------- | --------- |
| Spada corta         |      1   |     6   | 1D6       |    
| Spadone             |      1   |     8   | 1D8       |
| Spadone ***Figo***  |      2   |    12   | 1D10+1    |



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

