This fork is so that this library actually works for me.

In conn.go on lines 242-243 this is what is in mmitton's version:

	go func() { chanResult <- message_packet.Packet }()
    // chanResult <- message_packet.Packet

In order for this library to work for me, I had to switch which lines are commented out.

If you want to see the full readme, check out [mmitton's version](http://github.com/mmitton/ldap).
