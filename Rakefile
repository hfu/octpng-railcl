task :default do
  #sh "wget --continue http://cyberjapandata.gsi.go.jp/xyz/experimental_railcl/mokuroku.csv.gz"
  sh "gzcat mokuroku.csv.gz | ruby map.rb | sort | ruby reduce.rb"
end
