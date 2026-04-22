# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'aa8e19e05f8b30d14b894fb2d94875bb6c8be3c6',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '728c3c982276c30244aad8f419f2dee2906289c5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ad9184e76a66b1001c29db9b0a3e87f646c64de0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ff5c50339cc1e9f34f04cb440a3e5fe89db0161d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f6a6f7ab165cedbfa2a7d0c93fe27a2d01ce09c8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '15a84652b94e465e9a7b25eb507193929863bc2f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7c46da2b39036a80ce088576d5794bf39e667f56',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'e2f236b273bfcd9c665306fdd53451b923d659ab',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '118f31f6ef3d26cb4d4d125ab16d08bb98193183',
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
