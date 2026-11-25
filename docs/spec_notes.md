# Few Points from Handwritten notes
the addr phase according to spec is one cycle only but it can be extended by the slave due the ext
ending the data phase of current transfer
the hready signal is given input to both master and slave but driven by the selected slave's HREADY
signal
hresp is given input to the master which indicates okay or error when the there errro respnose in two
cycles and master can change the it htrans based on the error respone in the first cycle if hready is
low
hready indicates whether tx is completed or extended

