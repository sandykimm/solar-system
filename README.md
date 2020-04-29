# solar-system

### how to run

```bash
$ git clone
```

1. go to your folder
2. open "host.bat" if on Windows, "host.command" if on Mac

if you're having trouble opening "host.command"— "The file “host.command” could not be executed because you do not have appropriate access privileges."

you need to set 'execute' on the file for it to allow you to run it:
```bash
$ chmod u+x /path/to/file.command
```
3. look in resulting console window and check if it contains a message beginning with "Serving HTTP on ..."— if not, you may not have Python installed; go download and install first.
4. now you're hosting a fake server— keep the window open.
5. open your web browser (preferably Google Chrome) and navigate to http://localhost:8000/ (assuming the console window's message said port 8000, if not, change the number in the URL to match.
6. observe!
