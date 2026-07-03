# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b53185b34e298b112153b630f1b49ed3a36fcfb2',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'be9744eb74f522c6829c5e8d842cc29dce8259bd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '8d56066eee52f490535afd5731d5ae2fffc85036',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '667f063adc0236664519d72d3f6d9ffd08afc757',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8d6039a455a7ecc7d2a592ff97f62db4e59b70bf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9fd87c33d003122d07169230030ed34cc6dd6bca',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'be84f565416a5b640f12ce20ce5355903c5176a3',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c0e15b2c46f9ae2314925cbbe9d97ed6ea8a717d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '94041a4dc49e0bde5cebe466f4123f30104a956b',
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
