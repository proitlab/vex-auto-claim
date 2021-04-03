# vex-auto-claim
Script to claim Vexanium reward

## Go to root folder

	cd /root

## Clone the git repository

	git clone https://github.com/proitlab/vex-auto-claim
	
## Copy the script into /root folder

	cp vex-auto-claim/*.ds /root
	
## Edit with vim or nano the auto-claim-rewards.ds

	nano auto-claim-rewards.ds
	
## Make auto-claim-rewards executable

	chmod 755 auto-claim-rewards.ds

## To run the script auto-claim-rewards.ds

	./auto-claim-rewards.ds

## Run check-auto-claim.ds from crontab every minute

	* *	* * *	root	/root/auto-claim-rewards.ds
