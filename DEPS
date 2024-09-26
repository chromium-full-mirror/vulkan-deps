# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '46ef757e048e760b46601e6e77ae0cb72c97bd2f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'd8ca3eedff0dbf0a62476e8df0d9c707a6886a7e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ec59c77a3bb5c747a369931ef101ac7c14823f2f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '44936c4a9d42f1c67e34babb5792adf5bce7f76b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '29f979ee5aa58b7b005f805ea8df7a855c39ff37',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '31cfa022eff1061a1ec8b3f1cd17b5b709fa6fee',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4c63e845962ff3b197855f3ae4907a47d0863f5a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '6fb0c125afec7b9d724d598f4dca6c61648be35f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '37d1faba30d6562a01f50327720678248909eb9e',
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
