# Neuralyne
Right now, Neuralyne is a proof of concept wrapper that dynamically allocates memory page size based on load, tested on stress-ng. In future, maybe someone smarter than me can make a gtk gui for this. It uses sysctl and stress-ng although the latter isn't needed if you edit the script, maybe this can also be used for ccx loading on Ryzen CPUs.

Installation (terminal in script directory)
chmod +x Neuralyne.sh
sudo ./Neuralyne.sh
