# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '13f219a6d65e710d108fcc8cf013a3d996a996a2',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '98254945250cdf47d66779d427bed964071d7271',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'fbf86836a9b1966586faf7be7bb8a6440e156d62',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b8c3b64b63758042576f6853d7f0abe9251460fa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '73814d006638aa00bd553215b054f0f02e457e22',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6766411fec2f1e712576e42724b465fa8273d7ec',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c38e7c390892e06fe4c84f0c19fb891c79f885d9',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '205badc9cf9ca28000fcea4b0addd50d75655c8c',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '75f0a41a61772e20ae6ddfc668bd4f3284be993c',
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
