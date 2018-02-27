# Ubuntu-and-php
Ubuntu 配置PHP开发环境


<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    Ubuntu配置PHP开发环境
</h3>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">安装git版本控制器</span><br/>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">sudo apt-get install git</pre>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">安装Nginx服务器</span>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">sudo apt-get install nginx</pre>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">安装PHP5和相关扩展</span>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">sudo apt-get install php5-cgi php5-curl php5-cli php5-fpm php5-mcrypt php5-mysql
sudo apt-get install php5</pre>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">安装mysql数据库</span>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">apt-get install mysql-server mysql-client</pre>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">安装redis数据库（缓存）</span>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">apt-get install php5-redis
apt-get install redis-server</pre>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">安装mongodb数据库</span>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">apt-get install mongodb
apt-get install php5-mongo</pre>
<h3 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: normal; line-height: 1.1; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 24px; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">最后我们在配置一下Nginx的配置（目录文件/etc/nginx/sites-available/default）</span>
</h3>
<pre class="brush:bash;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">sudo vi /etc/nginx/sites-available/default
#修改 “index” 为：index index.html index.htm index.php;
#修改 “root” 目录为： root /var/www;
#找到以下内容，把对应的前面#注释去掉，其中fastcgi_param SCRIPT_FILENAME $document_root是要添加的，若不添加，打开php网页都是空白页；
#参考如下：
location ~ \.php$ {
    #fastcgi_split_path_info ^(.+\.php)(/.+)$;
    #NOTE: You should have &quot;cgi.fix_pathinfo = 0;&quot; in php.ini
    #With php5-cgi alone:
    #fastcgi_pass 127.0.0.1:9000;    
    #With php5-fpm:
    fastcgi_pass unix:/var/run/php5-fpm.sock;
    fastcgi_index index.php;
    fastcgi_param SCRIPT_FILENAME $document_root$fastcgi_script_name;
    include fastcgi_params;
}</pre>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;"></span><span style="box-sizing: border-box; font-size: 14px; color: rgb(0, 176, 80);">PS:别忘记重启Nginx</span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">然后我们去/var/www/ 目录下创建一个phpinfo.php 文件 并且写入</span>
</p>
<pre class="brush:php;toolbar:false" style="box-sizing: border-box; overflow: auto; font-family: Menlo, Monaco, Consolas, &quot;Courier New&quot;, monospace; font-size: 13px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; color: rgb(51, 51, 51); word-break: break-all; word-wrap: break-word; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">&lt;?php
    echo phpinfo();</pre>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    然后在浏览器中访问 127.0.0.1/phpinfo.php 然后我们就会看到PHP的相关 信息。如图
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <img src="http://www.piaoyifa.com/uploads/image/1519568061332349.jpeg" title="1519568061332349.jpeg" alt="1517440005254718.jpeg" class="img-responsive" width="688" height="269"/>
</p>
<p>
    <br/>
</p>
