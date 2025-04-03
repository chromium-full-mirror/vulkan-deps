# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c3d39de93955f884e443c39e9ffecf86e4aac883',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '54eddbe9fcf33a6b5e77b8044f332cea872fc704',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '8e82b7cfeca98baae9a01a53511483da7194f854',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '4bd1536ed79003a5194a4bd8c9aa2fa17a84c15b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2ac81691baf291e7f4aad07596d7073974dbc4dd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '723d6b4aa35853315c6e021ec86388b3a2559fae',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '289efccc7560f2b970e2b4e0f50349da87669311',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '551221d913cc56218fcaddce086ae293d375ac28',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e1dce162a5d73cd2da36cdcedf8a714cb85c23eb',
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
