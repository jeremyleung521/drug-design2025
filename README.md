# Drug Design 2025 Class Instructions
https://www.github.com/jeremyleung521/drug-design2025

A repository with Drug Design 2025 Class Files

# Quick Start Guide
* Follow `venv_instructions.pdf`

## Logging in
1.	Go to https://jupyter.crc.pitt.edu
* Login with your Pitt ID/Password
* Click "Start Server"
* Select the "Teach 1-gpu 3 hours"

## Setting up files and stuff
2.	Open a terminal and run the following:
* ``python -m pip install nglview``
*	``git clone https://github.com/jeremyleung521/drug-design2025``
*	``source ~/drug-design2025/run_bash.sh``
*	Stop your server and restart.
*	If Firefox, make sure Enhanced Tracking Protection is off (little shield icon next to URL)

## Activating environment
3.	After everything is done, you should be in ``~/drug-design2025``
* A virtual environment called ``drug-design2025`` is made in ``~/``
* To use venv, select the correct kernel (Top right of Notebook) or run ``source ~/drug-design2025/activate_env.sh`` (Terminal)

Notes:
* Everything in ``$TMPDIR`` will be deleted when your session terminates (TIMEOUT, SLURM job deleted/canceled and/or by clicking “Stop my server” on the CRC website)
* You can reconnect even when your browser disconnects (nothing deleted)
* Your environment (built in ``~/``) will be preserved. Run ``source ~/drug-design2025/activate_env.sh`` (Sets environment variables and activates environment: drug-design2025/bin/activate, clones this repository into $TMPDIR if doesn't exist).
* If the kernel is acting weird (can't import things even after kernel restart), just stop your server and restart. (File --> Hub Control Panel --> Stop My Server). Run ``source ~/drug-design2025/activate_env.sh`` to reclone the repository + activate environment.
