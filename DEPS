# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8c056be60a4223da78f9ba9f730fe1397be4209d',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '2a089520f7d5f5107160a9318e5ed1b757159519',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f2e4bd213104fe323a01e935df56557328d37ac8',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '84c917b958000db3040752ffc1ae0dee8d2d945d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '766aaabe571fa32c53606085775340b78ab8d728',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8a25939012fb114404594ac0a64478275faa88e6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5f090a13d0629694036efb104f8633af69ba3ce7',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'e7f2656f161f578e000ec967d4c0cc3fc33c5c52',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd9a7182d996a0b1174b1d806b18ccec32227ae1a',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
