# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6334e1549a49989e04b5329a6a39a328247fd6ed',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e0bc3e4fd14ef1109c5e62b55c827b93a9138c76',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'fb1379425b16e58dcbdda7be0f8604a7f5cdce78',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3c8fd35297315682906894621677f1b7003461ef',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd277a0a3cda9c682708c93279f0c72cd6b0ae3f3',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7acda38054d8f1d7cfb056d0acb77c41955e5ae7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '01d98ef3721bf2a3bf5a1b09ba24b43eb2232fa8',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9f11befc94670d692521529fad93429655dd4083',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c70feb60f7280eaf70357bc2389ebc3b77ba0db2',
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
