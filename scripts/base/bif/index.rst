:orphan:

Package: base/bif
=================


:doc:`/scripts/base/bif/const.bif.zeek`

   Declaration of various scripting-layer constants that the Bro core uses
   internally.  Documentation and default values for the scripting-layer
   variables themselves are found in :doc:`/scripts/base/init-bare.zeek`.

:doc:`/scripts/base/bif/types.bif.zeek`

   Declaration of various types that the Bro core uses internally.

:doc:`/scripts/base/bif/bro.bif.zeek`

   A collection of built-in functions that implement a variety of things
   such as general programming algorithms, string processing, math functions,
   introspection, type conversion, file/directory manipulation, packet
   filtering, interprocess communication and controlling protocol analyzer
   behavior.
   
   You'll find most of Bro's built-in functions that aren't protocol-specific
   in this file.

:doc:`/scripts/base/bif/stats.bif.zeek`


:doc:`/scripts/base/bif/reporter.bif.zeek`

   The reporter built-in functions allow for the scripting layer to
   generate messages of varying severity.  If no event handlers
   exist for reporter messages, the messages are output to stderr.
   If event handlers do exist, it's assumed they take care of determining
   how/where to output the messages.
   
   See :doc:`/scripts/base/frameworks/reporter/main.zeek` for a convenient
   reporter message logging framework.

:doc:`/scripts/base/bif/strings.bif.zeek`

   Definitions of built-in functions related to string processing and
   manipulation.

:doc:`/scripts/base/bif/option.bif.zeek`

   Definitions of built-in functions that allow the scripting layer to
   change the value of options and to be notified when option values change.

:doc:`/scripts/base/bif/plugins/Bro_SNMP.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_KRB.types.bif.zeek`


:doc:`/scripts/base/bif/event.bif.zeek`

   The protocol-independent events that the C/C++ core of Bro can generate.
   
   This is mostly events not related to a specific transport- or
   application-layer protocol, but also includes a few that may be generated
   by more than one protocols analyzer (like events generated by both UDP and
   TCP analysis.)

:doc:`/scripts/base/bif/logging.bif.zeek`

   Internal functions and types used by the logging framework.

:doc:`/scripts/base/bif/comm.bif.zeek`

   Functions and events regarding Bro's broker communication mechanisms.

:doc:`/scripts/base/bif/messaging.bif.zeek`

   Functions for peering and various messaging patterns.

:doc:`/scripts/base/bif/data.bif.zeek`

   Functions for inspecting and manipulating broker data.

:doc:`/scripts/base/bif/store.bif.zeek`

   Functions to interface with broker's distributed data store.

:doc:`/scripts/base/bif/input.bif.zeek`

   Internal functions and types used by the input framework.

:doc:`/scripts/base/bif/analyzer.bif.zeek`

   Internal functions and types used by the analyzer framework.

:doc:`/scripts/base/bif/file_analysis.bif.zeek`

   Internal functions and types used by the file analysis framework.

:doc:`/scripts/base/bif/__load__.zeek`


:doc:`/scripts/base/bif/zeekygen.bif.zeek`

   Functions for querying script, package, or variable documentation.

:doc:`/scripts/base/bif/pcap.bif.zeek`


:doc:`/scripts/base/bif/bloom-filter.bif.zeek`

   Functions to create and manipulate Bloom filters.

:doc:`/scripts/base/bif/cardinality-counter.bif.zeek`

   Functions to create and manipulate probabilistic cardinality counters.

:doc:`/scripts/base/bif/top-k.bif.zeek`

   Functions to probabilistically determine top-k elements.

:doc:`/scripts/base/bif/plugins/__load__.zeek`


:doc:`/scripts/base/bif/plugins/Bro_ARP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_BackDoor.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_BitTorrent.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_ConnSize.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_ConnSize.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DCE_RPC.consts.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DCE_RPC.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DCE_RPC.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DHCP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DHCP.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DNP3.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_DNS.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_File.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Finger.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_FTP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_FTP.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Gnutella.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_GSSAPI.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_GTPv1.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_HTTP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_HTTP.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_ICMP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Ident.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_IMAP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_InterConn.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_IRC.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_KRB.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Login.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Login.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_MIME.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Modbus.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_MySQL.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NCP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NCP.consts.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NetBIOS.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NetBIOS.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NTLM.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NTLM.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NTP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_POP3.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_RADIUS.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_RDP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_RDP.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_RFB.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_RPC.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SIP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SNMP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_check_directory.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_close.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_create_directory.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_echo.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_logoff_andx.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_negotiate.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_nt_create_andx.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_nt_cancel.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_query_information.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_read_andx.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_session_setup_andx.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_transaction.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_transaction_secondary.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_transaction2.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_transaction2_secondary.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_tree_connect_andx.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_tree_disconnect.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_com_write_andx.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb1_events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_close.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_create.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_negotiate.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_read.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_session_setup.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_set_info.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_tree_connect.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_tree_disconnect.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_write.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_com_transform_header.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.smb2_events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.consts.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMB.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMTP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SMTP.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SOCKS.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SSH.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SSH.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SSL.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SSL.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SSL.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SSL.consts.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SteppingStone.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Syslog.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_TCP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_TCP.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Teredo.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_UDP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_VXLAN.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_XMPP.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_FileEntropy.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_FileExtract.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_FileExtract.functions.bif.zeek`

   Internal functions used by the extraction file analyzer.

:doc:`/scripts/base/bif/plugins/Bro_FileHash.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_PE.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Unified2.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_Unified2.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_X509.events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_X509.types.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_X509.functions.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_X509.ocsp_events.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_AsciiReader.ascii.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_BenchmarkReader.benchmark.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_BinaryReader.binary.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_ConfigReader.config.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_RawReader.raw.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SQLiteReader.sqlite.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_AsciiWriter.ascii.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_NoneWriter.none.bif.zeek`


:doc:`/scripts/base/bif/plugins/Bro_SQLiteWriter.sqlite.bif.zeek`


