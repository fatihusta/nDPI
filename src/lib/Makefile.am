bin_PROGRAMS = ndpi_network_list_compile
AM_CPPFLAGS = -I$(top_srcdir)/src/include/  -I$(top_srcdir)/src/lib/third_party/include/

CFLAGS += -fPIC -DPIC -DNDPI_LIB_COMPILATION # --coverage

libndpi_a_includedir = $(includedir)/libndpi-@VERSION@/libndpi

BUILT_SOURCES = ndpi_network_list.c.inc

libndpi_a_include_HEADERS = ../include/ndpi_api.h \
			     ../include/ndpi_define.h \
			     ../include/ndpi_main.h \
			     ../include/ndpi_includes.h \
			     ../include/ndpi_config.h       \
			     ../include/ndpi_protocol_ids.h \
			     ../include/ndpi_protocols.h    \
			     ../include/ndpi_typedefs.h     \
			     third_party/include/ndpi_md5.h \
			     third_party/include/ndpi_sha1.h \
			     third_party/include/libcache.h \
			     third_party/include/ht_hash.h

libndpi_a_SOURCES = ndpi_content_match.c.inc \
		     ndpi_network_list.c.inc \
		     ndpi_main.c \
		     ndpi_utils.c \
		     ndpi_analyze.c \
		     ndpi_classify.c \
		     ndpi_serializer.c \
		     ndpi_geoip.c \
		     protocols/afp.c \
		     protocols/ajp.c \
		     protocols/aimini.c \
		     protocols/among_us.c \
		     protocols/amazon_video.c \
		     protocols/applejuice.c \
		     protocols/apple_push.c \
		     protocols/armagetron.c \
		     protocols/ayiya.c \
		     protocols/amqp.c \
		     protocols/bgp.c \
		     protocols/bittorrent.c \
		     protocols/bjnp.c \
		     protocols/capwap.c \
		     protocols/checkmk.c \
		     protocols/ciscovpn.c \
		     protocols/citrix.c \
		     protocols/cpha.c \
		     protocols/coap.c \
		     protocols/collectd.c \
		     protocols/corba.c \
		     protocols/crossfire.c \
		     protocols/csgo.c \
		     protocols/dcerpc.c \
		     protocols/dhcp.c \
		     protocols/dhcpv6.c \
		     protocols/diameter.c \
		     protocols/directconnect.c \
		     protocols/directdownloadlink.c \
		     protocols/dns.c \
		     protocols/dnscrypt.c \
		     protocols/dnp3.c \
		     protocols/dofus.c \
		     protocols/drda.c \
		     protocols/dropbox.c \
		     protocols/eaq.c \
		     protocols/edonkey.c \
		     protocols/fasttrack.c \
		     protocols/fiesta.c \
		     protocols/fix.c \
		     protocols/florensia.c \
		     protocols/ftp_control.c \
		     protocols/ftp_data.c \
		     protocols/git.c \
		     protocols/gnutella.c \
		     protocols/gtp.c \
		     protocols/guildwars.c \
		     protocols/hangout.c \
		     protocols/h323.c \
		     protocols/halflife2_and_mods.c \
		     protocols/http.c \
		     protocols/iax.c \
		     protocols/icecast.c \
		     protocols/imo.c \
		     protocols/iec60870-5-104.c \
		     protocols/ipp.c \
		     protocols/irc.c \
		     protocols/jabber.c \
		     protocols/kakaotalk_voice.c \
		     protocols/kerberos.c \
		     protocols/kontiki.c \
		     protocols/ldap.c \
		     protocols/lotus_notes.c \
		     protocols/lisp.c \
		     protocols/mail_imap.c \
		     protocols/mail_pop.c \
		     protocols/mail_smtp.c \
		     protocols/maplestory.c \
		     protocols/megaco.c \
		     protocols/memcached.c \
		     protocols/mining.c \
		     protocols/mgcp.c \
		     protocols/modbus.c \
		     protocols/mongodb.c \
		     protocols/mpegts.c \
		     protocols/mqtt.c \
		     protocols/mssql_tds.c \
		     protocols/mysql.c \
		     protocols/nats.c \
		     protocols/nest_log_sink.c \
		     protocols/netbios.c \
		     protocols/netflow.c \
		     protocols/nintendo.c \
		     protocols/nfs.c \
		     protocols/noe.c \
		     protocols/non_tcp_udp.c \
		     protocols/ntp.c \
		     protocols/openft.c \
		     protocols/openvpn.c \
		     protocols/ookla.c \
		     protocols/oracle.c \
		     protocols/postgres.c \
		     protocols/ppstream.c \
		     protocols/pptp.c \
		     protocols/qq.c \
		     protocols/quic.c \
		     protocols/radius.c \
		     protocols/rdp.c \
		     protocols/redis_net.c \
		     protocols/rsync.c \
		     protocols/rtcp.c \
		     protocols/rtmp.c \
		     protocols/rtp.c \
		     protocols/rtsp.c \
		     protocols/rx.c \
		     protocols/s7comm.c \
		     protocols/sflow.c \
		     protocols/shoutcast.c \
		     protocols/sip.c \
		     protocols/skinny.c \
		     protocols/skype.c \
		     protocols/smb.c \
		     protocols/snmp_proto.c \
		     protocols/soap.c \
		     protocols/socks45.c \
		     protocols/sopcast.c \
		     protocols/soulseek.c \
		     protocols/spotify.c \
		     protocols/ssdp.c \
		     protocols/ssh.c \
		     protocols/starcraft.c \
		     protocols/stealthnet.c \
		     protocols/steam.c \
		     protocols/stun.c \
		     protocols/syslog.c \
		     protocols/targus_getdata.c \
		     protocols/tcp_udp.c \
		     protocols/teamspeak.c \
		     protocols/teamviewer.c \
		     protocols/telegram.c \
		     protocols/telnet.c \
		     protocols/tftp.c \
		     protocols/thunder.c \
		     protocols/tls.c \
		     protocols/teredo.c \
		     protocols/tvuplayer.c \
		     protocols/ubntac2.c \
		     protocols/usenet.c \
		     protocols/viber.c \
		     protocols/vhua.c \
		     protocols/vmware.c \
		     protocols/vnc.c \
		     protocols/warcraft3.c \
		     protocols/websocket.c \
		     protocols/whoisdas.c \
		     protocols/world_of_kung_fu.c \
		     protocols/world_of_warcraft.c \
		     protocols/wsd.c \
		     protocols/xbox.c \
		     protocols/xdmcp.c \
		     protocols/zattoo.c \
		     protocols/zeromq.c \
		     protocols/smpp.c \
		     protocols/tinc.c \
		     protocols/someip.c \
		     protocols/whatsapp.c \
		     protocols/wireguard.c \
		     protocols/zabbix.c \
		     third_party/include/libahocorasick.h \
		     third_party/include/ndpi_patricia.h \
		     third_party/include/libcache.h \
		     third_party/src/libahocorasick.c \
		     third_party/src/ht_hash.c \
		     third_party/src/ndpi_md5.c \
		     third_party/src/ndpi_sha1.c \
		     third_party/src/libinjection_html5.c \
		     third_party/src/libinjection_sqli.c \
		     third_party/src/libinjection_xss.c \
		     third_party/src/libcache.c \
		     third_party/src/btlib.c \
		     third_party/src/ndpi_patricia.c

lib_LIBRARIES = libndpi.a

libndpi_a_CPPFLAGS = -I$(top_srcdir)/src/include/  -I$(top_srcdir)/src/lib/third_party/include/ 
#@HS_INC@

#EXTRA_DIST = third_party/src/ndpi_patricia.c

PROTO_CFG_FILES = $(wildcard ndpi_network_list_*.yaml)

ndpi_network_list.c.inc: $(PROTO_CFG_FILES) ndpi_network_list_compile
		./ndpi_network_list_compile -o $@ $(PROTO_CFG_FILES)

