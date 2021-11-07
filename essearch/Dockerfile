FROM elasticsearch:6.8.20
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch ingest-attachment && \

yum-config-manager --add-repo https://download.opensuse.org/repositories/home:/Alexander_Pozdnyakov/CentOS_7/ && \ rpm --import https://build.opensuse.org/projects/home:Alexander_Pozdnyakov/public_key && \ 
yum update -y && \ 
yum install tesseract tesseract-langpack-de tesseract-langpack-en && \ 
yum clean all
