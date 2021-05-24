# keylogger_python

/*pour convertir le code en fichier.exe*/

from cx_Freeze import setup, Executable

setup(
	name="MonSuperProgramme",
	version="0.1",
	description="keylogger",
	executables=[Executable("Keylogger.py")]
)
