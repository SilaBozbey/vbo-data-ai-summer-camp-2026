# Text-to-SQL Data Assistant (n8n Projesi)

n8n ve LLM (Groq) entegrasyonu kullanarak doğal dildeki soruları PostgreSQL SQL sorgularına dönüştüren yapay zeka destekli otomasyon projesidir.

Bu proje, kullanıcıların karmaşık SQL sorguları yazmak yerine doğal bir dille (sohbet eder gibi) veri tabanından bilgi alabilmesini sağlamak amacıyla n8n platformu üzerinde geliştirilmiştir.

##Kullanılan Teknolojiler

n8n: İş akışı ve otomasyon yönetimi
LLM (Groq / AI Agent): Doğal dil işleme ve SQL koduna dönüştürme
PostgreSQL: Veritabanı yönetimi ve sorgulama
##Dosyalar

text-to-sql_data_assistant.json: n8n iş akışı dışa aktarma (export) dosyasıdır. Kendi n8n ortamınıza içe aktararak (import) doğrudan kullanabilirsiniz.
