# Few Points from Handwritten notes
the addr phase according to spec is one cycle only but it can be extended by the slave 
the hready signal is given input to both master and slave but driven by the selected slave's HREADY
signal
hresp is given input to the master which indicates okay or error when the transfer completes
hready indicates whether tx is completed or extended

