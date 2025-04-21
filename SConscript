from building import *
import rtconfig
Import('RTT_ROOT')

# get current directory
cwd = GetCurrentDir()
src = []
path = []

if GetDepend(['SOC_CY8C624ABZI_S2D44']):
    src += Glob('COMPONENT_CAT1A/COMPONENT_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1A']

if GetDepend(['SOC_CY8C6245LQI_S3D72']):
    src += Glob('COMPONENT_CAT1A/COMPONENT_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1A']

if GetDepend(['SOC_CY8C624ALQI_S2D42']):
    src += Glob('COMPONENT_CAT1A/COMPONENT_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1A']

if GetDepend(['SOC_CY8C6247BZI_D54']):
    src += Glob('COMPONENT_CAT1A/COMPONENT_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1A']

if GetDepend(['SOC_CY8C6347BZI_BLD53']):
    src += Glob('COMPONENT_CAT1A/COMPONENT_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1A']

if GetDepend(['SOC_CY8C6244LQI_S4D92']):
    src += Glob('COMPONENT_CAT1A/COMPONENT_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1A']

if GetDepend(['SOC_XMC7200D_E272K8384AA']):
    src += Glob('COMPONENT_CAT1C/COMPONENT_XMC7x_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1C']

if GetDepend(['SOC_XMC7100D_F144K4160AA']):
    src += Glob('COMPONENT_CAT1C/COMPONENT_XMC7x_CM0P_SLEEP/*.c')
    path += [cwd + '/COMPONENT_CAT1C']
group = DefineGroup('Libraries', src, depend=[''], CPPPATH=path)
Return('group')
