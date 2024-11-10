# laringoscopiot: Dados Poc

Repositório que contém os dados obtidos durante os testes da prova de conceito do laringoscópiot

## Descrição dos dados:

**camera_stream.csv** - dataset com cada frame capturado, seu timestamp e a resolução do frame. Montado a partir dos logs da câmera diretamente pelo ffmpeg.

**wireshark-sensor-logs.pcap** - arquivo exportado do Wireshark que contém todos os logs da transmissão de dados da rede durante a execução dos testes de desempenho.

**sensors_packets.csv** - dataset com cada um dos pacotes de transmissão dos dados dos sensores já filtrados. Montado a partir do arquivo de logs do wireshark.
