# hello-world
try the repository

elseif  string.find(string.lower(url),"^/order/bookorder.aspx") then    
      local uri = ngx.re.sub(string.lower(ngx.var.args), "^classid=(.*)", "/$1/getbook", "o")
      ngx.req.set_uri(uri)
      return "qamc_hujiang_com_tradeapi"
