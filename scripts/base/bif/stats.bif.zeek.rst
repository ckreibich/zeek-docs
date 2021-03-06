:tocdepth: 3

base/bif/stats.bif.zeek
=======================
.. zeek:namespace:: GLOBAL


:Namespace: GLOBAL

Summary
~~~~~~~
Functions
#########
========================================================= =======================================================
:zeek:id:`get_broker_stats`: :zeek:type:`function`        Returns statistics about Broker communication.
:zeek:id:`get_conn_stats`: :zeek:type:`function`          Returns Bro traffic statistics.
:zeek:id:`get_dns_stats`: :zeek:type:`function`           Returns statistics about DNS lookup activity.
:zeek:id:`get_event_stats`: :zeek:type:`function`         Returns statistics about the event engine.
:zeek:id:`get_file_analysis_stats`: :zeek:type:`function` Returns statistics about file analysis.
:zeek:id:`get_gap_stats`: :zeek:type:`function`           Returns statistics about TCP gaps.
:zeek:id:`get_matcher_stats`: :zeek:type:`function`       Returns statistics about the regular expression engine.
:zeek:id:`get_net_stats`: :zeek:type:`function`           Returns packet capture statistics.
:zeek:id:`get_proc_stats`: :zeek:type:`function`          Returns Bro process statistics.
:zeek:id:`get_reassembler_stats`: :zeek:type:`function`   Returns statistics about reassembler usage.
:zeek:id:`get_reporter_stats`: :zeek:type:`function`      Returns statistics about reporter messages and weirds.
:zeek:id:`get_thread_stats`: :zeek:type:`function`        Returns statistics about thread usage.
:zeek:id:`get_timer_stats`: :zeek:type:`function`         Returns statistics about timer usage.
========================================================= =======================================================


Detailed Interface
~~~~~~~~~~~~~~~~~~
Functions
#########
.. zeek:id:: get_broker_stats

   :Type: :zeek:type:`function` () : :zeek:type:`BrokerStats`

   Returns statistics about Broker communication.
   

   :returns: A record with Broker statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_conn_stats

   :Type: :zeek:type:`function` () : :zeek:type:`ConnStats`

   Returns Bro traffic statistics.
   

   :returns: A record with connection and packet statistics.
   
   .. zeek:see:: get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_dns_stats

   :Type: :zeek:type:`function` () : :zeek:type:`DNSStats`

   Returns statistics about DNS lookup activity.
   

   :returns: A record with DNS lookup statistics.
   
   .. zeek:see:: get_conn_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_event_stats

   :Type: :zeek:type:`function` () : :zeek:type:`EventStats`

   Returns statistics about the event engine.
   

   :returns: A record with event engine statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_file_analysis_stats

   :Type: :zeek:type:`function` () : :zeek:type:`FileAnalysisStats`

   Returns statistics about file analysis.
   

   :returns: A record with file analysis statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_gap_stats

   :Type: :zeek:type:`function` () : :zeek:type:`GapStats`

   Returns statistics about TCP gaps.
   

   :returns: A record with TCP gap statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_matcher_stats

   :Type: :zeek:type:`function` () : :zeek:type:`MatcherStats`

   Returns statistics about the regular expression engine. Statistics include
   the number of distinct matchers, DFA states, DFA state transitions, memory
   usage of DFA states, cache hits/misses, and average number of NFA states
   across all matchers.
   

   :returns: A record with matcher statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_net_stats

   :Type: :zeek:type:`function` () : :zeek:type:`NetStats`

   Returns packet capture statistics. Statistics include the number of
   packets *(i)* received by Bro, *(ii)* dropped, and *(iii)* seen on the
   link (not always available).
   

   :returns: A record of packet statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_proc_stats

   :Type: :zeek:type:`function` () : :zeek:type:`ProcStats`

   Returns Bro process statistics.
   

   :returns: A record with process statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_reassembler_stats

   :Type: :zeek:type:`function` () : :zeek:type:`ReassemblerStats`

   Returns statistics about reassembler usage.
   

   :returns: A record with reassembler statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_reporter_stats

   :Type: :zeek:type:`function` () : :zeek:type:`ReporterStats`

   Returns statistics about reporter messages and weirds.
   

   :returns: A record with reporter statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_timer_stats
                get_broker_stats

.. zeek:id:: get_thread_stats

   :Type: :zeek:type:`function` () : :zeek:type:`ThreadStats`

   Returns statistics about thread usage.
   

   :returns: A record with thread usage statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_timer_stats
                get_broker_stats
                get_reporter_stats

.. zeek:id:: get_timer_stats

   :Type: :zeek:type:`function` () : :zeek:type:`TimerStats`

   Returns statistics about timer usage.
   

   :returns: A record with timer usage statistics.
   
   .. zeek:see:: get_conn_stats
                get_dns_stats
                get_event_stats
                get_file_analysis_stats
                get_gap_stats
                get_matcher_stats
                get_net_stats
                get_proc_stats
                get_reassembler_stats
                get_thread_stats
                get_broker_stats
                get_reporter_stats


