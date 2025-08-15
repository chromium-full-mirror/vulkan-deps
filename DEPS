# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c6793af9ab988750614dd116def22131a0c03860',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '4aa602af36fe9518ca5d1d90c0ee51f986eaca2a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e6d5e88c07cc66a798b668945e7fb29ec1cfee27',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '96ede18e530987f87f880bc21fe159dc998de884',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2e0a6e699e35c9609bde2ca4abb0d380c0378639',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '022c002293038e482dbc0f61b20664d0b25d3a24',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0eb12b4ea70b15be6a10f6212c1633e5c9ce0cca',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4f4c0b6c61223b703f1c753a404578d7d63932ad',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd565666636721eef9ba7706202e9d12971a81acb',
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
