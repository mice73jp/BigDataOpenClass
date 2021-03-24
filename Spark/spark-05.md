* File format
    * 파일 압축
        * 여러가지 압축형식 지원
        * Split가능 여부가 BottleNeck을 피하기 위한 방법
            * 복수의 노드에서 읽기 가능 여부가 됨
* FileSystem
    * Locak filesystem
    * Amazon S3
    * HDFS(Hadoop Distributed File System)
* Spark SQL
    * Apache Hive
        * Get HiveContext
        * Hive Query Language
            * Get HiveRDD
    * JSON
        * Hive에서 Json파일 로드
        * SQL로 Json구조를 구조적으로 취득
            * `{"user": {"name": "Matei", "location": "Berkeley"}, "text": "Even nicer here :)"}`
            * `Select usr.name, text FROM tweets`
* 데이터베이스
    * JDBC(Java Database Connectivity)
        * JdbcRDD
        * ClassforName
        * lowBound, upperBound
        * 기본 배열 오브젝트
        * resultSet의 특정 필드만 얻는 오브젝트
    * Cassandra