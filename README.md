ConstantineMMORPG_Scripts

클라이언트 - 서버 간 TCP/IP 통신을 통해 진행되는 게임의 되는 코드 입니다.

사용언어 : 클라이언트(C#) / 서버 (C# .NET CORE )

ConstantineMMORPG\protoc-3.12.3-win64\bin\protocol.proto 파일에서 패킷을 생성한 후, GetProto.bat 파일을 클릭하면
클라이언트와 서버 모두에서 사용할 수 있는 패킷이 생성됩니다.

이후 서버와 클라이언트의 세션을 연결한 후, 이 패킷을 통해 서로 통신하고 그 통신에 맞는 처리를 각 부분(Server/Client) 에서 하는 구조입니다.
