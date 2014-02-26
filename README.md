xmodem-1k
=========

Georges Menie's Xmodem with minor modifications:

 * Support Xmodem-1K transfers
 * Don't send a final (empty) packet on transfers that are
   exact multiples of the packet size, to make it work with some
   Xmodem receivers.
