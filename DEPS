# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1d47ffa8ac4374a19b302021e216a20f22a3de92',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7c0cdc3d90b7508bd36ea99c1784cf4913c5119e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6bb105b6c4b3a246e1e6bb96366fe14c6dbfde83',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '05b0ab1253db43c3ea29efd593f3f13dfa621ab1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'df274657d83f3bd8c77aef816c1cbf27352a948b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e1cad037970cfeeb86051c49d00ead75311acbec',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7f6326618226225269a274869ac638b870c8fe2b',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ea43e2f5e51e9ad958a40fdce981f2f0abf09cb5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f35e17f6d208150c3ae01519808ec7dc837eb2dc',
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
