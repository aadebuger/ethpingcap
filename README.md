# ethpingcap
# error
Exception during reset or similar
Traceback (most recent call last):
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/sqlalchemy/pool.py", line 709, in _finalize_fairy
    fairy._reset(pool)
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/sqlalchemy/pool.py", line 880, in _reset
    pool._dialect.do_rollback(self)
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/sqlalchemy/dialects/mysql/base.py", line 1804, in do_rollback
    dbapi_connection.rollback()
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/pymysql/connections.py", line 432, in rollback
    self._read_ok_packet()
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/pymysql/connections.py", line 396, in _read_ok_packet
    pkt = self._read_packet()
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/pymysql/connections.py", line 656, in _read_packet
    packet_header = self._read_bytes(4)
  File "/Users/aadebuger/GEXT/ethereumvenv3/lib/python3.6/site-packages/pymysql/connections.py", line 702, in _read_bytes
    CR.CR_SERVER_LOST, "Lost connection to MySQL server during query")
pymysql.err.OperationalError: (2013, 'Lost connection to MySQL server during query')



internalError: (pymysql.err.InternalError) (9001, 'PD server timeout[try again later]') (Background on this error at: http://sqlalche.me/e/2j85)
