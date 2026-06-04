# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '98beacdbe5d99f4ac5e4c58bc02bb16c6aeee515',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '11e4ae3b615e81648a984790006350876225c3d2',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1e770e7de8373a8dd49f23416cf7ca4001d01040',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9b51d3d78717e29efd75adf1856cdbcc644eda7a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '015e25c3c91b70eb1a754d36fb14c4ba6ad9b0b9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9fe2d47e9cc784133b85026db18e0f4622a6beec',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e3d18f90c0b8ef1f52539e0674a42f0adfe30381',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '8383c46b129c2b3a5f3833e602d946d2fcc57e39',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b8a9b941cf99af1c83e92fd50bff6655fb6c1c38',
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
