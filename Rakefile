task default: %w[p]

task :up do
  sh 'docker-compose up -d'
  sleep 10
  sh 'open http://localhost:4567'
end

task :p do
  sh 'git add .'
  # sh 'git pull'
  sh 'git commit -m "update"'
  sh 'git push'
end
