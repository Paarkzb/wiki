build:
	@echo Building server...
	go build -o dist/wiki.exe ./src
	@echo Server built!

start: build
	@echo Starting server...
	cmd /c start /B ./dist/wiki.exe
	@echo Server running!

stop:
	@echo Stopping the server...
	@taskkill /IM wiki.exe /F
	@echo Stopped server!