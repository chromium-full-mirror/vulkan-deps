# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f5d2960bbd08bcabe003eaf07a2569f897587d44',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e1013f570e4fab64a29328dd75c925ce8888e181',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '58006c901d1d5c37dece6b6610e9af87fa951375',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6337eb62cadd7d124ac6789bf39c0f71148f0a73',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0e9de566b7d4051c5cc1b762e242c46565956bdf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '506124c4ac349c7a515ab71fdd460f285fae71bd',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '353f23f2c0bdf90bce0df551633c5ed873f530ba',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '8752119a6a407bac16313d38f3e935c8d619b089',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4e821ec91264400d075a5260a61817d05beae5ee',
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
