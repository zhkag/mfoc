Import('RTT_ROOT')
Import('rtconfig')
from building import *

cwd = GetCurrentDir()
src = Glob('*.c')
CPPPATH = [cwd]

group = DefineGroup('mfoc', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
