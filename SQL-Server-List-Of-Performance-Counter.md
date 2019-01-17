# List of performance counters for SQL Server

This can be useful for monitoring with PRTG.

Sensori

SQL Memory
\Memory\Pages/sec::pages/sec
\Memory\Page Faults/sec::pages/sec
\Memory\Pages Input/sec::pages/sec
\Memory\Pages Output/sec::pages/sec
\Memory\Page Reads/sec::pages/sec
\Memory\Page Writes/sec::pages/sec
\Memory\Available Bytes::bytes
\SQLServer:Buffer Manager\Buffer cache hit ratio::%
\SQLServer:Buffer Manager\Checkpoint pages/sec::pages/sec
\SQLServer:Buffer Manager\Page life expectancy::sec
\SQLServer:Buffer Manager\Lazy writes/sec::writes/sec
\SQLServer:Memory Manager\Memory Grants Pending::processes
\SQLServer:Memory Manager\Target Server Memory (KB)::kb
\SQLServer:Memory Manager\Total Server Memory (KB)::kb

SQL Requests
\Processor Information(_Total)\% Privileged Time::%
\System\Context Switches/sec::switches/sec
\System\Processor Queue Length::#
\SQLServer:SQL Statistics\Batch Requests/sec::requests/sec
\SQLServer:SQL Statistics\SQL Compilations/sec::comp/sec
\SQLServer:SQL Statistics\SQL Re-Compilations/sec::re-comp/sec

SQL Locks
\SQLServer:Locks(_Total)\Number of Deadlocks/sec::lock/sec
\SQLServer:Locks(_Total)\Lock Requests/sec::requests/sec
\SQLServer:Locks(_Total)\Average Wait Time (ms)::ms

SQL Access Methods
\SQLServer:Access Methods\Full Scans/sec::scan/sec
\SQLServer:Access Methods\Index Searches/sec::searches/sec
\SQLServer:Access Methods\Page Splits/sec::split/sec
\SQLServer:Access Methods\Worktables Created/sec::tables/sec

SQL Tempdb
\PhysicalDisk(x)\% Disk Time::%
\PhysicalDisk(x)\Avg. Disk Queue Length::n
\PhysicalDisk(x)\Avg. Disk sec/Read::IO/sec
\PhysicalDisk(x)\Avg. Disk sec/Write::IO/sec
\PhysicalDisk(x)\Disk Reads/sec::IO/sec
\PhysicalDisk(x)\Disk Writes/sec::IO/sec
\PhysicalDisk(x)\Current Disk Queue Length::n
# x:disknumber tempdb
# recuperare il numero da Disk Management (gestione disco), Esempio:
\PhysicalDisk(1 E:)\% Disk Time::%
\PhysicalDisk(1 E:)\Avg. Disk Queue Length::n
\PhysicalDisk(1 E:)\Avg. Disk sec/Read::IO/sec
\PhysicalDisk(1 E:)\Avg. Disk sec/Write::IO/sec
\PhysicalDisk(1 E:)\Disk Reads/sec::IO/sec
\PhysicalDisk(1 E:)\Disk Writes/sec::IO/sec
\PhysicalDisk(1 E:)\Current Disk Queue Length::n
