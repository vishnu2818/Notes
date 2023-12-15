#hibernate.cfg.xml File
<hibernate-configuration>
<session-factory>
<property name="hibernate.connection.driver_class">com.mysql.cj.jdbc.Driver</property>
<property name="hibernate.connection.username">root</property>
<property name="hibernate.connection.password">root</property>
<property name="hibernate.connection.url">jdbc:mysql://localhost:3306/DBName?createDatabaseIfNotExist=true</property>
<property name="hibernate.dialect">org.hibernate.dialect.MySQL5Dialect</property>
<property name="hibernate.show_sql">true</property>
<property name="hibernate.hbm2ddl.auto">update</property>
</session-factory>
</hibernate-configuration>
