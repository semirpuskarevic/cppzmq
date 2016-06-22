project('cppzmq', 'cpp')

zmq_dep = dependency('libzmq', required : true)
cppzmq_inc = include_directories('.')
cppzmq_dep = declare_dependency(include_directories : cppzmq_inc, dependencies : zmq_dep)
