from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c')
CPPPATH = [cwd]
group   = DefineGroup('WebTerminal', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
